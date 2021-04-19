```yaml
apiVersion: v1
kind: Human
metadata:
  name: project-xyz-final
  labels:
    pronouns: he/him/his
    nickname: Rom
    origins: Belgium
spec:
  humain:
    - name: Romuald
      image: pc-bf:1981.07
      command: ["/bin/sh"]
      args: ["-c", 'git clone --single-branch --branch dev https://github.com/pc-bf/baby.git; cd baby; ./configure; make; ./run-life']
      env:
        - name: Country
          value: "Netherlands"
        - name: Town
          value: "Eindhoven"
        - name: Job
          value: "Cloud Solution Architect"
```
Note: this is an ephemeral deployment, no persistent volume needed.
<!--
**rovandep/rovandep** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
