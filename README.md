# UI Speed Runs
Let's learn to build UI faster by doing speed runs.

It started with [this tweet](https://twitter.com/trafnar/status/1691213118989590528) where I asked who can make a todo list UI the fastest. The rules were very loosely specified.

The goal is to see how fast you can build a functional todo list UI (lets do different UIs in the future?). The goal is to learn, not to win. A slower entry might still teach us something. You can choose to add more functionality or styling. I think we will naturally see which entries have the best speed to quality ratio.

I'm most interested in UI code, not full-stack applications, you can of course build a full-stack app, but my main concern is how quickly I can "express" a UI, not build a functioning real word app.

I want to build UI faster, so if someone has a drastically faster way to build this, I want to know what that is!

# Contribute a Speed Run

Record a screencast (ideally narrate it!) and share the code. You can create an issue or PR here with your submission, or send it on Twitter.

## Proposed loose specification:

<img width="932" alt="Screenshot 2023-08-18 at 9 54 11 AM" src="https://github.com/trafnar/ui-speed-run/assets/6732/96cd9ef0-c093-476f-8353-e2b0cd42c246">

Functions:
- Add a todo to the list
- Delete a todo from the list
- Edit the todo title
- Check off / toggle a todo item
- Blank state message, "No todos"

Considerations:
- Prevent empty todo titles (when adding or editing a todo)
- Style finished todos differently (cross out the title for example)
- No need to persist data


# Submissions

These are the first few submissions based on the original tweet, which left it very open to interpretation.

**Pablo ([@paoloricciuti](https://twitter.com/PaoloRicciuti))**
- Time: ~18m
- Tech: Svelte
- [Screencast](https://www.loom.com/share/bb43acc9e7db4950a1392ffc23aa1b61?sid=6f6b3f97-946d-47b7-86a8-b99c3253e5bc)
- [Live](https://www.sveltelab.dev/zxgs57h2maykxti)

**Nathan [@trafnar](https://www.twitter.com/trafnar)**
- Time: ~20m
- Tech: Imba
- [Screencast](https://www.youtube.com/watch?v=FVn29JTQyjg)
- [Repo](https://github.com/wedeserveless/sppeeedytodo/blob/main/src/App.imba)
- [Live demo](https://speedy-todo.netlify.app/)

**Reaper ([@barelyreaper](https://www.twitter.com/barelyreaper))**
- Time: ~35m
- Tech: Typescript / ([thestack](https://github.com/barelyhuman/thestack))
- [Screencast](https://www.youtube.com/watch?v=ld8bBI0RtK0)
- [Repo](https://github.com/barelyhuman/todo-challege-30-min)
