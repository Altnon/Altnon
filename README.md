<!-- BANNER HERE -->
<h1 align="center">Hi There!</h1>

<p align="center">
  <a href="https://altnon.itch.io/"><img src="https://img.shields.io/badge/itch.io-FA5C5C?style=for-the-badge&logo=itch.io&logoColor=white" /></a>
  <a href="https://github.com/altnon"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="mailto:ellenoirbe@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://canva.link/bilar-resume"><img src="https://img.shields.io/badge/Resume-333333?style=for-the-badge&logo=read.cv&logoColor=white" /></a>
</p>

<p align="center">
  <i>I'm Ellenoir Bilar a gameplay programmer that also dables in technical art. I specialize in creating the core systems for my games but when that is out of the way I spend my time creating shaders and tools to help the design process.</i>
</p>

---
```csharp

public enum DevClass { GameplayProgrammer, TechnicalArtist, SystemsProgrammer }
public enum GameEngine { Unity, Unreal }
public enum GameProjects {BiscuitGremlins, SignalNo5, FromAllThatIWas, TheTinyTimeKeeper}

public class Profile : MonoBehaviour
{
    public GameProjects ActiveProject  = GameProjects.TheTinyTimeKeeper;
    [SerializeField] private DevClass primaryClass = DevClass.GameplayProgrammer;
    [SerializeField] private GameEngine currentEngine = GameEngine.Unity;
}
```
<!-- PROGRAMMING BREAKDOWN HERE -->
<h2 align="center">Main Projects</h2>


## Signal No. 5 - Project Manager, Programmer
<table width="100%">
  <tr>
    <td width="50%" valign="middle" align="center">
      <img src="https://github.com/Altnon/Altnon/blob/main/Assets/Showcase_SignalNo5.gif" width="100%" style="border-radius: 8px; aspect-ratio: 16/9; object-fit: cover;" alt="Vortex VFX Preview">
      <p align="center" style="margin-top: 10px;">
        <a href="https://altnon.itch.io/signal-no-5"><img src="https://img.shields.io/badge/Play-itch.io-FA5C5C?style=flat-square&logo=itch.io&logoColor=white"></a>
      </p>
    </td>

  <td width="50%" valign="middle" style="padding-left: 15px;">  
    <ul style="padding-left: 20px margin:0;">
      <li style= "margin-bottom:12px">
        <b>Toon Shader</b><br>
        <sub>Created a Cel Shader for the characters to add a more cartoon effect</sub>
      </li>
      <li style= "margin-bottom:12px">
        <b>Rising Flood Logic with Shader</b><br>
        <sub>Light objects can float while heavy objects sink visibility of objectsdepend on position in the water</sub>
      </li>
      <li style= "margin-bottom:12px">   
        <b>Couch Coop Logic</b><br>
        <sub>Characters are moved with two plugged-in controllers using tank controls</sub>
      </li>
      <li style= "margin-bottom:12px">  
        <b>Electrical VFX</b><br>
        <sub>Creating a electric effect that activates in intervals that would damagethe player</sub>
      </li>
      <li style= "margin-bottom:12px">
        <b>Wave VFX</b><br>
        <sub>Created a wave effect that quickly comes in from the window asset with water droplets</sub>
      </li>
  </td>
  </tr>
</table>

## From All That I Was - Project Manager, Programmer
<table width="100%">
  <tr>
    <td width="50%" align="center" style="vertical-align: middle;">
      <img src="https://github.com/Altnon/Altnon/blob/main/Assets/Showcase_FromAllThatIWas.gif" width="100%" style="border-radius: 8px; aspect-ratio: 16/9; object-fit: cover;">
      <p align="center" style="margin-top: 10px;">
        <a href="https://sharkbyte-studios.itch.io/from-all-that-i-was"><img src="https://img.shields.io/badge/Play-itch.io-FA5C5C?style=flat-square&logo=itch.io&logoColor=white"></a>
      </p>
    </td>
    <td width="50%" style="vertical-align: middle; padding-left: 15px;">
      <ul style="padding-left: 20px margin:0;">
        <li style= "margin-bottom:12px">
          <b>Glow VFX</b><br>
          <sub>Created glow effect to make the mask more apparent and ethereal compared to the environment</sub>
        </li>
         <li style= "margin-bottom:12px">
          <b>Hallway Exposition Logic</b><br>
          <sub>Adjusted the mood of the hallway after obtaining cards</sub>
        </li>
        <li style= "margin-bottom:12px">
          <b>Card Selection Logic</b><br>
          <sub>Card selection works by pressing the left mouse button moves the card to a designated slot filling it from right to left</sub>
        </li>
    </td>
  </tr>
</table>

<h2 align="center">Other Works</h2>

<table align="center">
  <tr>
    <td align="center" width="33%" height="20%">
      <h3>Explosion VFX</h3>
      <a href="Assets/ExplosionVFX.gif"><img src="https://github.com/Altnon/Altnon/blob/main/Assets/ExplosionVFX.gif" width="100%" alt="Explosion"></a>
    </td>
    <td align="center" width="33%" height="20%">
      <h3>Biscuit Gremlins</h3>
      <a href="https://roewaviii.itch.io/biscuit-gremlin"><img src="https://img.itch.zone/aW1hZ2UvMzgzOTM4OC8yMjk3MTUxMi5wbmc=/original/kyuRAQ.png" width="100%" alt="Biscuit"></a>
    </td>
    <td align="center" width="33%" height="20%">
      <h3>Vortex VFX</h3>
      <a href="Assets/VortexVFX.gif"><img src="https://github.com/Altnon/Altnon/blob/main/Assets/VortexVFX.gif" width="100%" alt="Vortex"></a>
    </td>
  </tr>
</table>

---
