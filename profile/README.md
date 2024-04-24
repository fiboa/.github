# *Fi*eld *Bo*undaries for *A*griculture

## About fiboa
The *Fi*eld *Bo*undaries for *A*griculture (fiboa) specification is the concrete result to emerge from the Field Boundary Initiative, the first iteration of [Taylor Geospatial Engine’s (TGE) Innovation Bridge Program](https://tgengine.org/taylor-geospatial-engines-first-innovation-bridge/). The TGE Field Boundary Initiative aims to enable practical applications of AI and computer vision to Earth observation imagery for a better understanding of global food security. The initiative has spurred collaboration between academia, industry, NGOs, and governmental organizations toward creating shared global field boundary datasets that can be used to create a more sustainable and equitable agriculture sector.

## Key Features
The fiboa specification represents field boundary data in GeoJSON & GeoParquet in a standard way, with several optional ‘extensions’ that specify additional attributes. The core data schema of fiboa is quite simple - it is a set of definitions for attribute names and values. The number of attributes in the core is quite small by design. The idea is that most of the ‘interesting’ data about the field will be located in ‘extensions’. 

There will likely be lots of different types of extensions: some that are generally accepted as the main way to do things in fiboa and widely understood by tools and others that are very niche and not widely used but valuable to a small number of users (e.g. an extension specific to a company or organization to help them better validate their data). 

You can learn more about the technologies behind the fiboa specification, read the full specification text, and explore available open data sets and extensions at the links below.

- [The Specification](https://github.com/fiboa/specification)
- [List of Tutorials](https://github.com/fiboa/tutorials)
- [List of Datasets](https://github.com/fiboa/data)
- [List of Extensions / Guide to Creating Extensions](https://github.com/fiboa/extensions)
- [List of Software / Tooling](https://github.com/fiboa/software)
  - [CLI: GeoParquet Validation, Conversion, etc. in Python](https://github.com/fiboa/cli)
- [Data Survey](https://github.com/fiboa/data-survey) 

## Developer Communication Channels
The fiboa community strives to provide a welcoming and transparent environment for all of the project’s participants. You can find additional information about our community’s best practices and collaborative development processes below:
- [Code of Conduct](https://github.com/fiboa/specification/blob/main/CODE_OF_CONDUCT.md)
- [Contribution Guideline](https://github.com/fiboa/specification/blob/main/CONTRIBUTING.md)
- [Development and Release Process](https://github.com/fiboa/specification/blob/main/process.md)

The fiboa developer community has a number of communication channels available for discussion and collaboration.

We encourage you to utilize our [Slack](https://cloudnativegeo.slack.com/archives/C06ET015VGS) for general and administrative questions.
You’re also welcome to attend the bi-weekly Zoom meetings where the research and developer community shares updates, discusses the roadmap, and gives the occasional live demonstration.
To get on the email list, please sign up for the [fiboa Google Group](https://groups.google.com/a/tgengine.org/g/fiboa).
Joining this Google Group will also get you a calendar invite for the bi-weekly meetings as well as any other general fiboa meetings.

- [Slack](https://cloudnativegeo.slack.com/archives/C06ET015VGS)
- [Google Group](https://groups.google.com/a/tgengine.org/g/fiboa)
- Open Discussions and issue trackers for specific topics:
  - [Specification related issues](https://github.com/fiboa/specification/issues)
  - [New extensions or high-level extension discussions](https://github.com/fiboa/extensions/issues)
  - [New software/tooling or high-level software/tooling discussions](https://github.com/fiboa/software/issues)
  - [New datasets or data-related issues](https://github.com/fiboa/data/issues)
  - [Missing learning resources or related issues](https://github.com/fiboa/tutorials/issues)
  - [Discussions that span multiple topics (e.g. specification, tooling, extensions)](https://github.com/fiboa/specification/discussions)
  - Discussions and issues around specific tooling or extensions goes into the [corresponding repositories](https://github.com/orgs/fiboa/repositories)

