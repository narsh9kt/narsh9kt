## Hi there 👋

<!--
**narshykt/narshykt** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

function createUser({ name, age, city }) {
  return {
    name,
    age,
    city,
    introduce() {
      console.log(`Hello there, my name is ${this.name}. I'm ${this.age} y.o. At the moment I live in ${this.city}.`);
    },
  }
}
