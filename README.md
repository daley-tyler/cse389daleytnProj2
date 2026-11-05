# Unreal Engine coursework scene

This is a historical Unreal Engine 5.5 coursework snapshot. It contains a scene at `Content/Tester.umap`, Epic Starter Content and the standard C++ game-module bootstrap. I keep it as a record of my earlier editor work rather than a finished game or a demonstration of custom gameplay code.

## Inspect the project

The project file is `cse389daleytnProj2.uproject`; its engine association is 5.5. Open it with Unreal Engine 5.5 and the appropriate C++ build tools, then open `Content/Tester.umap` in the editor. The configured default map is Unreal's OpenWorld template, so opening the project does not automatically select the coursework scene.

These paths and settings were checked against the repository. Editor loading, asset references, packaging and runtime behavior have not been revalidated. There are no automated tests, packaged builds or verified gameplay demonstrations in this snapshot. The desktop rendering configuration enables ray tracing and other demanding features; cross-platform compatibility is unverified.

The optional Android File Server is disabled, and its checked-in development token has been cleared. If using that feature later, generate a new local token before enabling it. The previous value remains in the original Git history.

## Attribution and scope

Epic supplied the engine templates, module bootstrap and Starter Content. The C++ bootstrap retains Epic's copyright notice. The included starter assets are not my original artwork. This repository does not grant a separate reuse license for Epic material or claim that the template code demonstrates original gameplay engineering.

For my current application work, start with [University Course Planner](https://github.com/daley-tyler/university-course-planner), [Speech Emotion Recognition](https://github.com/daley-tyler/speech-emotion-recognition) or [Article Retrieval Chatbot](https://github.com/daley-tyler/article-retrieval-chatbot).
