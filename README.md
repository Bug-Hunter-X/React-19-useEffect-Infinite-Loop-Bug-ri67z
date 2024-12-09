# React 19 useEffect Infinite Loop Bug

This repository demonstrates a common error in React 19 involving the `useEffect` hook that can lead to an infinite rendering loop. The bug occurs when an effect's dependency array includes a value that is modified within the effect itself, creating a cycle where the effect continuously triggers and updates the state, causing an infinite loop.  The solution shows how to fix this by correctly managing dependencies and preventing this unintended behavior.