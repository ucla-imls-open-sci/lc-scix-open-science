---
title: 'Intro to SciX and FAIR principles'
teaching: 15
exercises: 5
---

::: questions

- What is FAIR?
- What is the social benefit of Open Science?
:::

::: objectives
- Define the FAIR principles and explain what each component (Findable, Accessible, Interoperable, and Reusable) means in the context of scientific data.
- Explain how SciX makes data **Findable** by assigning unique, persistent identifiers and indexing rich metadata.
- Describe how SciX supports **Accessibility** through standardized retrieval protocols and the use of an API.
- Illustrate how SciX promotes **Interoperability** by incorporating standard vocabularies and qualified references within its metadata.
- Discuss how SciX enhances **Reusability** by ensuring metadata includes clear licensing, detailed provenance, and adherence to community standards.
:::

## Lesson Content

Data supporting scientific research can be difficult to find in many fields. Papers often describe data collection and methods, but rarely include the actual data alongside the manuscript. As articles move online, publishers are still not typically equipped to store and distribute datasets.

In response, standards were needed to guide data infrastructure. This led to the development of the FAIR Principles for Scientific Data--first described in a 2016 Nature article. FAIR stands for **Findable, Accessible, Interoperable,** and **Reusable.** Each term has been expanded into guiding principles for developing resource platforms like SciX.

### Findable Principles

The focus is on making data easy to locate by both humans and computers. This is achieved by creating machine-readable metadata that is essential for automated discovery:

- **F1:** Data and metadata are assigned a globally unique and persistent identifier.
- **F2:** Data are described with rich metadata (as defined further in R1).
- **F3:** Metadata clearly and explicitly include the identifier of the data they describe.
- **F4:** Data and metadata are registered or indexed in a searchable resource.

### Accessible Principles

These principles help users understand how to retrieve data:

- **A1:** Data and metadata are retrievable by their identifier using a standardised communications protocol. 
    - **A1.1:** The protocol is open, free, and universally implementable.
    - **A1.2:** The protocol supports authentication and authorisation, where necessary.
- **A2:** Metadata remain accessible even when the data are no longer available.

### Interoperable Principles

Data often needs to be integrated with other data, used in workflows, or transformed for processing:

- **I1:** Data and metadata use a formal, accessible, shared, and broadly applicable language for knowledge representation.
- **I2:** Data and metadata use vocabularies that follow FAIR principles.
- **I3:** Data and metadata include qualified references to other data and metadata.

### Reusable Principles

The goal is to ensure data can be reused in various contexts:

- **R1:** Data and metadata are richly described with a variety of accurate and relevant attributes. 
    - **R1.1:** Data and metadata are released with a clear and accessible data usage license.
    - **R1.2:** Data and metadata are associated with detailed provenance.
    - **R1.3:** Data and metadata meet domain-relevant community standards.

Although SciX exemplifies all four FAIR principles, its primary focus is on being a discovery platform--making data **Findable.** Each article in SciX is assigned a unique, persistent identifier that not only retrieves the article but also connects related papers via citations. Every reference is described with detailed metadata (including title, authors, abstract, publication, and keywords) that is fully indexed and searchable. When data is included, it is also assigned an identifier.

SciX further supports **Accessibility** by providing an API for standardized, programmatic retrieval of records. When an article cites supporting references, the citation information is included as part of the metadata, supporting **Interoperability.** Finally, by following established publication standards and associating metadata with its provenance, SciX ensures that data is **Reusable** in various contexts.

::::::::::::::::: discussion
## Benefits of FAIR Science

What do you think are the social benefits of making scientific data FAIR?
:::::::::::::::::

::::::::::::::::: discussion
## Benefits of Open Science to your community/institution

Encourage a discussion on how open science can benefit your community or institution.

::::

:::: discussion

## Reflection

For the final 5 minutes, display prompts on the screen:

- How does SciX make research data more discoverable?
- In what ways does open access to metadata support open science?

Please share your thoughts with the class.

::::

:::::::::::::::::::::::::::::::::::::::: keypoints

- The FAIR principles provide a framework for making scientific data more discoverable and usable.
- SciX makes data Findable by assigning unique, persistent identifiers and indexing rich metadata.
- SciX ensures Accessibility through standardized retrieval protocols and a robust API.
- By using standard vocabularies and qualified references, SciX promotes Interoperability.
- Detailed metadata with clear licensing and provenance supports Reusability of research data.

::::::::::::::::::::::::::::::::::::::::::::::::::
