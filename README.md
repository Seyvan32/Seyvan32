<!-- Header Banner -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Seywan%20Jahani&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Game%20Developer%20|%20VR%20Enthusiast%20|%20Code%20Architect&descAlignY=52&descSize=18"/>
</div>

<!-- Typing SVG -->
<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6E57F7&center=true&vCenter=true&random=false&width=524&lines=3%2B+Years+of+Game+Development+Experience;Unreal+Engine+%26+Unity+Specialist;Building+Immersive+VR+Experiences;Passionate+About+Interactive+Worlds" alt="Typing SVG" />
  </a>
</p>

<!-- Social Badges -->
<p align="center">
  <a href="https://linkedin.com/in/seywanjahani"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://twitter.com/alexmorgan_dev"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white"/></a>
  <a href="https://seywanjahani.dev"><img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white"/></a>
  <a href="mailto:seywanjahani@email.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://discord.gg/none"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"/></a>
</p>

<!-- Profile Views Counter -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=seywanjahani&style=for-the-badge&color=6E57F7"/>
  <img src="https://img.shields.io/github/followers/seywanjahani?style=for-the-badge&color=6E57F7&labelColor=1a1a2e"/>
</p>

---

## 🎮 About Me

```csharp
public class GameDeveloper : Human, IDeveloper
{
    public string Name { get; } = "Seywan Jahani";
    public string Location { get; } = "Mashhad, IR";
    public int YearsOfExperience { get; } = 3.5;
    
    public string[] Roles { get; } = new string[]
    {
        "Mid-Level Game Developer",
        "VR Specialist"
    };
    
    public string CurrentFocus { get; } = "Building next-gen VR experiences";
    
    public Dictionary<string, string[]> Expertise => new()
    {
        ["Languages"] = new[] { "C#", "C++", "TypeScript", "Python" },
        ["Engines"] = new[] { "Unity", "Unreal Engine 5", "CocosCreator" },
        ["VR/AR"] = new[] { "Meta Quest", "SteamVR", "WebGL", "ARCore" },
        ["Specializations"] = new[] { "Physics Systems", "AI", "Multiplayer" }
    };
    
    public void GetMotivation() => Console.WriteLine("Creating worlds people escape into! 🚀");
}
