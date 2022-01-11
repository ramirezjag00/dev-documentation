# Dev Onboarding Documentation?

> compilation of tech documentation ideas by n00n3xx
> 


> 💡 Anything that could possibly get devs up to speed, tech set up, feel comfortable and confident, the faster they can produce quality code, learn more and contribute.
>
> Documentations can be as simple as README in a separate repository (ie. readme for each role) or using frameworks like docusaurus for APIs / libraries or using JSDoc/TSDoc/TypeDoc for codebase/block documentation or Storybook for components or using Notion for all documentations.
>
> The team can be as verbose or consise as they want. It doesn't matter to me 😛 as long as any dev level won't get lost while reading your 💩.
>
> There are a lot of open source projects that documents description & alternatives, how an individual can start contributing, see existing/closed issues, which features are merged and all change logs.
>
> Another example is the  [mattermost](https://developers.mattermost.com/contribute/getting-started/) documentation, or in a form of [tech blog (by react native)](https://reactnative.dev/blog) or in a form of [working group](https://github.com/reactwg) (check any repo) or [discussions](https://github.com/reactwg/react-18/discussions) (for react-18)

### What to add? 🤔

- team
    - team/squad structure/overview including QAs PMs and backend devs
    - relevant tech channels (chat)
    - point of contact(s) and what they do?
- codebase
    - get started: description and how to run the app (readme.md)
    - folder structure (file tree) of project, with description
    - app screens and flows (screenshots and description)
        - can be by product / module / flow
    - codebase architecture? data fetching? local db? apis? enviroments? etc
    - current state of the code base
    - high-level / general plan for the future of codebase / road map
    - API Docs and/or chat/channels where api json for postman is always posted and updated
- resources:
    - HOW-TOs
        - ie. benchmarking, performance optimizations, testing etc
    - best practices relevant to project / overall?
    - dev/debugging tools ie. react-native-debugger / flipper
    - list of internal admin/dashboard tools/websites and the credentials
    - learning resources
    - project documentation(s) written by Business Analysts - business requirements translated to developer-ready docs 😂
- processes
    - git strategies / process specific to team/squad
    - scrum / processes from develop → testing → release → scrum ceremonies → sprint planning cycle

>
>💡 for a long-term approach of a well-maintained codebase
>
> - [git tagging](https://git-scm.com/docs/git-tag) to keep track of all codebase versions (releases, beta etc) + [changelog.md](https://keepachangelog.com/en/1.0.0/) to keep track of whatever a certain version has
>
> - using issues tab of git repos (with proper tagging and details) to keep track of any issues solved, existing ones, temporary/band-aid fixes, any documentation, maintainance, announcements etc.
