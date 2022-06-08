 <div align="center">
   <img width="100" src="img/recoil.png" />
 </div>

<h1 align="center">
    Learn Recoil
</h1>

<div align="center">
 <span>Introductory study on Recoil</span>
</div>


<p align="center">🚧 WIP 🚧</p>

**References:**
- [RecoilJS](https://recoiljs.org/)
- [learnrecoil](https://learnrecoil.com)
- [recoil-course](https://github.com/jacques-blom/recoil-course)

<details>
<summary>Overview & Setup</summary>

- **Why build Recoil?** Large number of rendered components that need to frequently update in isolation.
    
- **Recoil’s Key Features:**
    - **“Fexible shared state”**
        - Boilerplate-free
        - As simple as get/set
        - Allows for code-splitting
    - **“Derived data”**
        - Data can be devrived safety and simply from state and other derived data
        - Access derived data the same way you’d access state
        - Devirev data can be synchronous or asynchronous
    - **“App-wide state observation”**
        - Read any part Recoil state
        - Observe changes to state
        - Persist application state
        - Rehydration (backwards compatible)
- **Why use Recoil?** When your component tree and state structure don’t match.
    - **React Context**
        - Here we have a dropdown that has the number state, which is passed to the `App` component where it contains both text and number fields.

            <img width="" src="img/react-context-1.png" />

        - When you celebrate the option in the dropdown whole number decimal the number state changes to decimal causing the value of the field to change.

            <img width="" src="img/react-context-2.png" />
    - **Recoil**
        - The solution to this would be to use `recoil` and keep the states defined as a component outside of React.

            <img width="" src="img/recoil-1.png" />
</summary>
</details>

<details>
    <summary>Atoms</summary>
</details>

<details>
    <summary>Selectors</summary>
</details>

<details>
    <summary>Families</summary>
</details>

<details>
    <summary>State Persistence</summary>
</details>

<details>
    <summary>Suspense</summary>
</details>

<details>
    <summary>Concurrent Mode</summary>
</details>

<details>
    <summary>State Observation</summary>
</details>

<details>
    <summary>Performance</summary>
</details>

<details>
    <summary>Testing</summary>
</details>

<details>
    <summary>Recoil Relay</summary>
</details>

<details>
    <summary>How states are used in React without Recoil</summary>
</details>