### Hi there 👋

<!--
**mkloar/mkloar** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
I'm a Software Developer.

![visitors](https://visitor-badge.glitch.me/badge?page_id=mkloar.mkloar)

[![Twitter: MihaK](https://img.shields.io/twitter/follow/MihaK87?style=social)](https://twitter.com/MihaK87)
[![Linkedin: MihaK](https://img.shields.io/badge/-mkloar-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/mkloar/)](https://www.linkedin.com/in/mkloar/)

```typescript
class AboutMeService implements IAboutMeService {
  private readonly _name: string;
  private readonly _birthYear: number;
 
  contructor() {
    this._name = "MK";
    this._birthYear = 1997;
  }
  
  public getRole(): string {
    return "Software Developer";
  }
  
  public sayHi(): string {
    return "Thanks for dropping by. If you find my work interesting, you can ping me on Linkedin or Twitter.";
  }
  
  public getProgrammingLanguages(): Map<Emoji, string> {
    return {
      🥇: "TypeScript/JavaScript",
      🥈: "C#"
    }
  }
  
  
  public getFrameworks(): Map<Emoji, string> {
    return {
      🥇: "React/Gatsby/NextJS",
      🥈: "Angular"
    }
  }

  public getHobbies(): string[] {
    return ["Fitness 💪", "Reading 📚", "Cooking 🍔"];
  }
  
}


const aboutMeService = diContainer.get<IAboutMeService>(TYPES.IAboutMeService);

aboutMeService.sayHi();
aboutMeService.getRole();
aboutMeService.getProgrammingLanguages();
aboutMeService.getFrameworks();
aboutMeService.getHobbies();
```

## ⚡ Skills

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Nodejs](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAF)
![GatsbyJS](https://img.shields.io/badge/Gatsby-663399?style=for-the-badge&logo=gatsby&logoColor=white)
![NextJS](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![CSharp](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![Amazon AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-330F63?style=for-the-badge&logo=gitlab&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/RASPBERRY%20PI-C51A4A.svg?&style=for-the-badge&logo=raspberry%20pi&logoColor=white)

## Can Develop On

![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white) or 
![Linux](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

## Music

![Spotify](https://img.shields.io/badge/Spotify-1ED760?&style=for-the-badge&logo=spotify&logoColor=white)

## 📈 Github Stats
![Github Stats](https://github-readme-stats.vercel.app/api?username=mkloar&count_private=true&show_icons=true&include_all_commits=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mkloar&hide=TeX&layout=compact)
