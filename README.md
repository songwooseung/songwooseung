<div align="center">

  ![header](https://capsule-render.vercel.app/api?type=Waving&color=000000&text=songwooseung&fontColor=FFFFFF&animation=fadeIn&fontAlignY=55)
#

  ###   Tech Stack  
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat&logo=C&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flate&logo=MySQL&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flate&logo=HTML5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flate&logo=CSS3&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flate&logo=Javascript&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=Notion&logoColor=white">
  <img src="https://img.shields.io/badge/Github-181717?style=flat&logo=Github&logoColor=white">
    
  #  
  ![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=songwooseung&show_icons=true&theme=tokyonight)
  ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=songwooseung&layout=compact&theme=tokyonight)


  # 
  name: Waka Readme

  on:
    schedule:
      # Runs at 12am IST
      - cron: '30 18 * * *'
    workflow_dispatch:
  jobs:
    update-readme:
      name: Update Readme with Metrics
      runs-on: ubuntu-latest
      steps:
        - uses: anmol098/waka-readme-stats@master
          with:
            WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
            GH_TOKEN: ${{ secrets.GH_TOKEN }}
</div>


