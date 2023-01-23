# A ToIP Core Terminology

<MetaNotes>*This text is a first draft in different ways:*

1. *The content (i.e. the proposal for managing the ToIP Core Terminology) is draft.*
2. *The content is an example of a text that needs to be 'post-processed', which means that it uses some conventions for referencing that need to be converted to references that can be correctly rendered.*

</MetaNotes>

**"Since in order to understand, one must first listen, learn to understand by listening"**<br/>  (adapted version of a saying by Rumi)

## Introduction

The prime objective of the [ToIP Concepts and Terminology Working Group (CTWG)](https://wiki.trustoverip.org/pages/viewpage.action?pageId=65700) is to enable individual members of [communities](community), such as ToIP Working Groups (WG) or Task Forces (TF), to understand the words and phrases that are used in that [community](community) ***in the same, single meaning***. This is to say that ***the differences in the individual understandings of words or phrases by different members of the same [community](community) do not pose any problems as they collaborate to serve their shared interests***. 

This suggests that (members of) a [community](community) need the ability and means to (a) establish and maintain (i.e.: [own](owner)) their own [terminology](terminology@ctwg), and (b) to ensure it is fit for the purpose of eliminating such misunderstandings. More concretely, they need the ability and means to create, maintain and improve the [definitions](definition@ctwg) that link [terms](term@ctwg) with the [concepts](concept@ctwg)/meanings that they agree are relevant for their collaboration, and perhaps also to document the ways of thinking ([mental models](mental-model@ctwg)) that are crucial to their work. 

Once a [community](community) has its [terminology](terminology@ctwg) in place, it needs a means to generate its [glossary](glossary@ctwg), which serves as the authoritive reference for the (crucial) terms used by its members. This [glossary](glossary@ctwg) is also a valuable reference document for a non-community member, as it helps him/her to (better) understand the (verbal or written) communications authored by that [community](community), i.e. it helps to 'map', or 'translate' the terms of that [community](community) to words or phrases that the person uses itself, which is prerequisite for effectively engaging with that [community](community).

The secondary objective of the [CTWG](https://wiki.trustoverip.org/pages/viewpage.action?pageId=65700) is to enable members of [ecosystems](ecosystem), such as ToIP itself, to establish 

- a set of [terms](term@ctwg) that have a 'good definition' (as defined at the end of [this document](https://www.researchgate.net/publication/352560909_On_Terminology_and_the_Resolution_of_Related_Issues)), which basically means that ***two arbitrary people that use that definition stand a very good chance of having the same individual understanding of what is meant***. 
- a set of [mental models](mental-model@ctwg) that describe relations and constraints between sets of such terms, thus providing the bases for ***arbitrary sets of people to have the same understanding of specific ways of thinking about a set of concepts***.

Such [terminologies](terminology) and [mental models](mental-model@ctwg) differ from those created for/by [communities](community) in the sense that it is basically just a repository of words and phrases that [communities](community) may adopt within their own [scopes](scope@ctwg). They have no other authority than what they can derive from being used in/by [communities](community). 

The benefit of creating and maintaining such [terminologies](terminology) and [mental models](mental-model@ctwg) lies in the fact that they can be developed with less of a bias of developers than if they were developed in a [community](community) (that is there to serve its own interests). As such, they may play an important role as different [communities](community) seek to establish a languate for cooperating with one another.

We conclude this introduction by saying that while the real work is in developing good [definitions](definition@ctwg) that relate [concepts](concept@ctwg) with [terms](term@ctwg), and in developing [mental models](mental-model@ctwg) that link them together, we also need artifacts that can communicate them. We assume such artifacts will be created from 'raw materials', such as wiki pages, or markdown files. Such artifacts include [glossaries](glossary@ctwg), [dictionaries](dictionary@ctwg), and other documents.

## Scope

The scope of the ToIP Core Terminology, that can be refered to using the [tag](tag@ctwg) `#toip`, consists of

- any person that somehow contributes to the (currently still undocumented) [overall ToIP objectives](https://trustoverip.org/objectives), e.g. by participating in a WG or TF, AND that somehow contributes to the realization of the `#toip`-objectives.
- the set of `#toip`-objectives, which (for starters) is to develop (a) good [definitions](definition@ctwg) that relate [concepts](concept@ctwg) with [terms](term@ctwg), and (b) [mental models](mental-model@ctwg) that link them together, that have the property of being recognized as valuable by at least two WGs/TFs whose members have obviously different backgrounds (e.g. techies - lawyers).

Out of scope are [definitions](definition@ctwg) that relate [concepts](concept@ctwg) with [terms](term@ctwg), and [mental models](mental-model@ctwg) that serve a purpose for only a smaller part of the ToIP community, e.g. technical terms, as it seems more appropriate for them to be managed in their own [scope](scope@ctwg). Still, such work can be modeled after what is described here.

## An (Initial) ToIP Core Terminology Management Process

The **purpose** of this process is to develop and/or maintain a set of terms, their definitions and other artifacts that are relevant for ensuring that ToIP members with highly different backgrounds can have the same understanding about the meaning of each such term.

The initial process will be run by (some? all? members of) the [CTWG](https://wiki.trustoverip.org/pages/viewpage.action?pageId=65700). It will follow the lifecycle as explained in the [ToIP Terminology Tooling vision](https://github.com/trustoverip/concepts-and-terminology-wg/blob/master/docs/tt-spec.md#Vision), which consists of an ingestion phase, a curation phase, and an export phase. It will also consist of a redering of the ToIP Core Terminology Glossary, and in future perhaps also the ToIP Dictionary.

### Ingestion

Ingestion is the phase where people make contributions for whatever they think needs improvement regarding the ToIP Core Terminology, up to the point where such a contribution can actually be adopted in the [corpus](corpus@ctwg). The decision to adopt a matured proposal is made by the [scope's](scope@ctwg) curators.

In order to enable both tech-savvy and other people to contribute, we will allow proposals for adding/changing/removing terms through the following means:

- **as a wiki page** in the [toip-terms wiki](https://github.com/trustoverip/toip-terms/wiki). The wiki page must be formatted such that it can be copied 1-1 into the corpus. It is up to the author(s) to signal CTWG of any modifications made that are to be transferred into the corpus. Such signalling, as well as further discussions, can be held in the slack channel **#concepts-terminology-wg**, or by other means that turn out to work.
- **as a git issue** for the [toip-terms repository](https://github.com/trustoverip/toip-terms/issues). The first message in the issue SHOULD be edited to ultimately become a text that is formatted in such a way that it can be copied 1-1 into the corpus. Subsequent messages can be used for discussion. The issue will be closed as soon as the first message is transferred into the corpus.
- **as a pull request** (PR) to the (not yet existing?) corpus repository. The contribution must be formatted such that if the PR is merged, there will be no conflict with other corpus contents.

### Curation

In order to reach and maintain the (high) quality standard we need for terms, good criteria have to be established for (transparently) deciding whether/when a contribution should be adopted (or not). W

- **may go into the ToIP Core Terminology corpus** (and what does not). For starters, it is proposed to allow term definitions and mental models to become part of the corpus.
- **actually does go into that corpus**, because it is fit for the purposes of the #toip [scope](scope@ctwg). It is suggested 
  - for terms, each contribution must minimally state the name of the term, and a description that readers can use to determine whether or not something is (an instance of) that term. If the term describes a concept that is developed in a mental model, a reference to that mental model should be given.
    Optionally, additional texts, e.g. providing a more casual description, examples, etc. may be added.
  - for mental models, each contribution must state the name of the mental model (so that people can refer to it while speaking), the purpose that the model intents to serve, a rationale for its relevance, a casual introduction to the mental model, and a formal description (with a figure) that specifies how the concepts relate to one another. Also, a definition for the term associated with each of the concepts must be available in the corpus.

Versioning of content will initially not be done; it will be addressed as soon as there is an actual and practical need for that.

## Export and Rendering

In order to automatically generate a ToIP Core Terminology [Glossary](glossary@ctwg) document, a CD/CI street needs to be implemented that ensures that whenever content that is within the #toip [scope](scope@ctwg) is committed to the corpus, this results in the (re)generation of that [Glossary](glossary@ctwg) document. 

