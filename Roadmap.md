# The Kraken Project ROADMAP 2022-2023

Our roadmap typically looks out 8-12 months and we establish topics we want to work on. When we execute on our roadmap, we keep learning and our assessment of some of the topics listed changes. As a result, we may add or drop topics as we go. After around 12 months we come together to develop the next roadmap.

## Values

Before we go into the details, let's start with our values that guide the development of Kraken. 

Kraken is a web standard rendering engine based on Flutter, the major target for kraken is 

- Easy to customize and extend, developers may install extensions to provide specific function for kraken.
- Lightweight and fast, performance trumps functionality.
- Basic web rendering capabilities, depending on W3C standards.
- Great user & developer experience.

## Glossary

- Roadmap: Which defines high level themes and features to be addressed in this timeframe.
- theme: A collection of topics.
- Iterations: We will work in monthly iterations on the items on the roadmap. Iterations are roughly month based, rather than week based.
- topic: A specific thing to be done.
- topic owner: One or more people who maintain and develop functionality related to the theme.
- milestone: A collection of topics that be done at end of some day. Generally speaking, a milestone starts on the first day of the month and ends on the last day.
- milestone owner: A person that manage the milestone, responsible for advancing the work.

> 🚀 means which is experimental.

## Themes

For 2022, we'll particularly focus in the following themes.

- Improve the stability of kraken, to reduce crash, memory leak and other factors that may affect stability.
- Improve the performance of kraken, establish the benchmark infrastructure.
- Improve the extensionality of kraken, guide to building a plugin community.
- W3C standard compatibility alignment, we should generate a compatibility completeness report to kraken.
- Incrementally improve already existing features.
- Let more community developers join the project governance.

## Stability

- Helps detect potential memory leaks and crash issues in code with continuous integration static scanning tools
- Limit potentially high-risk logic with stricter code lint rules
- Generate the code implementation of the interface description through the generator mechanism
- Detect possible memory leaks by adding continuous integration for memory increments

## Performance

- Build the infrastructure of benchmark, collect performance data including the first screen, and display it on the official website
- Reduce the basic consumption of memory and CPU by optimizing logic
- Use miallocate instead of built-in memory allocator
- 🚀 Improve above-the-fold experience through instruction loading and instruction caching
- 🚀 Improve rendering performance with command grading
- 🚀 Improve rendering experience with instruction sharding
- 🚀 Built-in web components, to improve performance, such as waterfall, map and so on.

## Extensionality

- Stable the API of extension.
- Provide HTMLView to provide a better reading experience for no-script users
- Build some officially maintained plugin, to guide to building a plugin community.
- 🚀 Explorer the embeded integration webview, provide multi-engine support.
- Provide guidance of multi page integtration.

## Web compatibility

- Continue to improve compatibility of W3C standards within the scope of support

## Developer

- Improve the experience of debugging tools.
- Provide ability of JS debug.

## Website and Documentation

- Improve the user experience of the website.
- Setup blogs at website, to share the tech detail of the working principle of each sub-module. Post at least one per month.

## Community Support

- We'll continue our work on GitHub that enable members of our community give us a hand triaging and resolving issues.
  - Improve our GitHub issue bots, examples:
    -  reject invalid incoming issues automatically
    -  detect issues of limited use that 'need more information' automatically
- Cultivate community contributors, to deeply participation in construction, not limited to contribute codes, solve issues, anwser questions, maintain website and more.
- Sharing externally, irregularly, including but not limited to articles, online and offline speeches, etc.
- Cooperate with Flutter team.

## Versions

- Usually we will iterate at least one version every month, and release a minor version every 2-3 months. If the version lags behind 2 major versions of Flutter, we will speed up the rhythm of the release version. This decision is finally approved by TSC .
- Each release has a milestone established by the release owner and a TSC meeting to discuss the features contained in that milestone. The version manager is responsible for following up the development progress of the specified version with the Topic owner.

## Summary

These are examples of some of the work we will be focusing on in the next 8-12 months. We continuously tune the plan based on feedback and we will provide more detail in each of our [monthly iteration plans](./Iteration-Plans). We will develop our next roadmap in around 12 months from now. Please follow along and let us know what you think!

