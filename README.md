# Next.js router.push Unexpected Behavior

This repository demonstrates a subtle issue encountered when using the `router.push` method in Next.js.  The issue occurs in a particular scenario (described below) and involves unexpected routing behavior.

## Description
The provided code snippet shows a simple component that utilizes `router.push` to navigate to '/another-page'. However, the navigation may fail or behave unpredictably under certain conditions, such as when the component is rendered within a specific context or lifecycle hook.