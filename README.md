# TFGBV tracking

A project started at the PeaceTech Hackathon at EPFL (March 2024) to support humanitarian work in witnessing and monitoring how armed actors may use technology-facilitated gender-based violence (TFGBV).

## First principles

> Women shall be especially protected against any attack on their honour, in particular against rape, enforced prostitution, or any form of indecent assault. -- _([Article 27](https://ihl-databases.icrc.org/en/ihl-treaties/gciv-1949/article-27) of the Geneva Convention)_

> Humanity and Impartiality are substantive principles, the ‘goals’ of humanitarian action. Neutrality and Independence are operational principles, ‘tools’ for humanitarian actors. Finally, Voluntary service, Unity and Universality are organizational principles; they provide the institutional foundations that enable a principled humanitarian action. -- _([Fundamental principles of the ICRC](https://blogs.icrc.org/cross-files/the-fundamental-principles-of-the-international-red-cross-and-red-crescent-movement/))_

See [CHALLENGE](CHALLENGE.txt) for more background.

The following Prototypes were developed at the hackathon:

## ["Not my Daugher"](https://loleg.github.io/nmd/)

An interactive story (browser based, using [Twinery](https://twinery.org/)) - introduces our challenge in an immersive way. It was written with the help of an open source LLM derived from Llama 2 by Rubra.ai.

## [Data Package](src/branch/main/Datasets)

Data collection (using the [Baserow](https://baserow.io/) platform) was done at the hackathon from several public data sources, in order to create an overview of regions of ongoing armed conflict, and some of the types of technologies being used to perpetrate TFGBV. In addition to our initial outputs, we propose a data [SCRAPING](SCRAPING.md) approach to broaden this effort.

## [Example CASES](CASES.txt)

Using an increasingly established typology of TFGBV from scientific literature, and exemplary anonymized case studies from human rights organizations, we can pool data together in a coherent way from relevant journalistic reports, research data, and legal proceedings. We propose to prototype this in Python within a [Jupyter notebook](https://jupyter.org), with NLM or LLM that can be trained on plaintext files to help with classification. As an example, we provide this in `CASES.txt`.




