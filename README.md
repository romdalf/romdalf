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
      image: pc-bf:1981.07-001
      command: ["/bin/sh"]
      args: ["-c", 'git clone --single-branch --branch matrix-rev-01 https://github.com/rovandep/pc-bf.git; cd battery; ./configure; make; ./run']
      env:
        - name: Country
          value: "Netherlands"
        - name: Town
          value: "Eindhoven"
        - name: Job
          value: "Principal Cloud Solution Architect"
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
