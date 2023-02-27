# Single Page Applications with Vue

**1.** What is the entrypoint of an application?
<!-- enter you answer in the space below -->
```
The place where the execution of the program/application begins. Usually something along the lines of "main" or "main function" me believes.
```
**2.** What is the difference between a vue `component` and `page`?
<!-- enter you answer in the space below -->
```
Well I think the router may only be able to go to pages and not components? And we use "page"s as well.. actual pages while we use "component"s as little components of reusable code. On another hand, this is a bit of a trick because pages ARE just vue components ;)
```
**3.** What feature of Vue can be used to repeat an element using a collection of data?
<!-- enter you answer in the space below -->
```
v-for
```
**4.** What are the three tags that make up a Vue component?
<!-- enter you answer in the space below -->
```
templte, script, style
```
**5.** What does the `L` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The *Liskov* substitution principle. The one where it's (wiki) definition makes like no fuckin sense aaaand it has a kind of annoying Russian name to remember THANKS
```
**6.** Which component in Vue does the vue-router use to mount pages onto?
<!-- enter you answer in the space below -->
```
router-view
```
**7.** What is the difference between the `AppState` and the state object within a component?
<!-- enter you answer in the space below -->
```
AppState is well.. like the *State* object of the whole App. Who would've guessed...
```
**9.** What is the responsibility of `Services` in our Vue projects?
<!-- enter you answer in the space below -->
```
The same as the responsibility of "Services" in all our other projects so far I think. Have functions that the controller calls to that actually can reach into and possibly manipulate AppState data.
```
**10.** Which file contains the root element of your Vue project?
<!-- enter you answer in the space below -->
```
The index.html I think?
```
**11.** The ______ tag is used to alter the styling of your entire Vue project.  Adding the ______ attribute to this tag will limit it to just the component it exists.  Fill in the blank.
<!-- enter you answer in the space below -->
```
style tag, scope attribute
```
**12.** What is the Vue method used to create watchable objects such as `state` or `AppState`?
<!-- enter you answer in the space below -->
```
ref
```