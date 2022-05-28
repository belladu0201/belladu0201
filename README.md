### Hi there 👋 This is Beibei Du~


- 🔭 I’m currently working on preparing for internships(DS/DA/BA/DI) and be ready for the master program (MIDS @ Duke).
- 🌱 I’m currently learning `Python and Pandas for Data Engineering` on Cousera and self-learning SQL.
- 👯 I’m looking to collaborate on data science projects.
- 🤔 I’m looking for help with some theories in data science related to mathmatics/computer science.
- 💬 Ask me about: Anything related to UCSD
- 📫 How to reach me: belladu0201@gmail.com
- 😄 Pronouns: She/Her/Hers
- ⚡ Fun fact: I have a one year old Ragdoll named Mochi.


name: Waka Readme

on:
  workflow_dispatch:
  schedule:
    # Runs at 12am UTC
    - cron: "0 0 * * *"

jobs:
  update-readme:
    name: Update this repo's README
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
