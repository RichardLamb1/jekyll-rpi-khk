---
title: "Sample Page"
description: "A sample page"
permalink: /pages/sample-page
layout: docs
---

# Sample Page
Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi pretium tellus duis convallis. Tempus leo eu aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas. Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent per conubia nostra inceptos himenaeos.

## H2
Quo causae epicurei dissentiet ut, option electram imperdiet pri ei. Mei an eligendi detraxit, ne veri habeo vix. At usu reque graece possit. Timeam appareat sit id. Pri at fugit novum, sea dicunt alterum gloriatur at.

### H3
Ex omnes singulis vim, at mutat laoreet sea, pro an putant iracundia. Est alia propriae an, qui patrioque constituam reprehendunt no. His dolor democritum an, vis dicat petentium at. Rebum dicant altera sea et.


#### H4
Ad blandit theophrastus mea. Eos at facilis gloriatur, per ex vitae antiopam. Zril persius invenire ut mei. Ei has nihil scribentur.

Has sale iusto ad, per ex posse concludaturque. Eu pro causae atomorum oportere, his corpora torquatos ex. Vel ut sensibus forensibus. Malis labore quo an, saperet conclusionemque usu et, quis causae feugiat per ei. Unum fastidii accumsan nec ut.

##### H5
Duo et verterem democritum reformidans. His in malis numquam nominati. Pro ne probo malis elaboraret, usu at meis porro assentior. Menandri qualisque vulputate ad duo, nec quod postulant moderatius ne, at nec postea quaerendum. Vis id saepe homero elaboraret.

###### H6
At mei regione philosophia. Vis id primis mandamus. Prima explicari vel ei, eam ut alii dictas ponderum. Melius vulputate sed ex. Et duo elitr interpretaris.

Unum facilis intellegebat cu quo, ea porro appareat complectitur pro. Vim zril saperet lucilius at, has in sale mediocritatem, summo error eu quo. Te eos causae voluptua. Eros dicam assentior et mea, vide accusam liberavisse cum at. No ullum ponderum mei.

Ad has minim noster repudiare. Libris nostro ullamcorper eam id, velit dicunt scripta id mea. Nec eu movet evertitur, quo odio corpora placerat cu. Ei vis brute malorum, usu id assentior gloriatur.

## Code
Syntax highlighting is supported! *Sample code courtesy of ChatGPT*
```js
// Simple JavaScript example: A to-do list manager

// An array to store our tasks
let todoList = [];

/**
 * Add a task to the list
 * @param {string} task - The task description
 */
function addTask(task) {
  todoList.push({
    text: task,
    completed: false, // new tasks start as incomplete
  });
  console.log(`Task added: "${task}"`);
}

/**
 * Mark a task as completed
 * @param {number} index - The index of the task in the list
 */
function completeTask(index) {
  if (todoList[index]) {
    todoList[index].completed = true;
    console.log(`Task completed: "${todoList[index].text}"`);
  } else {
    console.log("Invalid task index.");
  }
}

/**
 * Display all tasks in the console
 */
function showTasks() {
  console.log("Your To-Do List:");
  todoList.forEach((task, i) => {
    // A ternary operator chooses ✔ or ✖ depending on task status
    let status = task.completed ? "✔" : "✖";
    console.log(`${i}. [${status}] ${task.text}`);
  });
}

// --- Example usage ---
addTask("Finish homework");
addTask("Go grocery shopping");
addTask("Clean the room");

showTasks();         // Display all tasks
completeTask(1);     // Mark "Go grocery shopping" as complete
showTasks();         // Display updated list
```
## Blockquotes
> A blockquote

{: .note }
> A note

{: .tip }
> A tip

{: .important }
> This is important

{: .warning }
> You have been warned

{: .caution }
> Words of caution

{: .note }
> A really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really really long note

{: .note }
> A note
> 
> With multiple
> 
> Lines

<blockquote class="note">
  <p>A note</p>
  <blockquote class="warning">
    <p>With a warning inside</p>
  </blockquote>
</blockquote>

## Lists
1. An
2. Ordered
3. List

- An
- Unordered
- List
