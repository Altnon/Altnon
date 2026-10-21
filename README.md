<!-- BANNER HERE -->
<h1 align="center">Hi There!</h1>

<p align="center">
  <a href="https://altnon.itch.io/"><img src="https://img.shields.io/badge/itch.io-FA5C5C?style=for-the-badge&logo=itch.io&logoColor=white" /></a>
  <a href="https://github.com/altnon"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="mailto:ellenoirbe@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p align="center">
  <i>I'm Ellenoir Bilar a gameplay programmer that also dables in technical art. I specialize in creating the core systems for my games but when that is out of the way I spend my time creating shaders and tools to help the design process.</i>
</p>

---
```csharp

public enum DevClass { GameplayProgrammer, TechnicalArtist, SystemsProgrammer }
public enum GameEngine { Unity, Unreal }
public enum GameProjects {BiscuitGremlins, SignalNo5, FromAllThatIWas, TheTinyTimeKeeper}

public class Profile : MonoBehaviour, IInteractiveDeveloper
{
    public GameProject ActiveProject  = GameProjects.TheTinyTimeKeeper;
    [SerializeField] private DevClass primaryClass = DevClass.GameplayProgrammer;
    [SerializeField] private GameEngine currentEngine = GameEngine.Unity;
}
```
---
<!-- PROGRAMMING BREAKDOWN HERE -->
---
