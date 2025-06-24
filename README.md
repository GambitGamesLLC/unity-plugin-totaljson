# unity-plugin-totaljson
Copy of the [TotalJSON Unity Plugin](https://assetstore.unity.com/packages/tools/input-management/total-json-130344).

**Assembly:**\
com.leguar.totaljson

**Namespace:**\
Leguar.TotalJSON

**ASMDEF File:**\
Leguar.TotalJSON

**Scripting Define Symbol:**\
EXT_TOTALJSON

------------------------------
ASSET STORE DESCRIPTION
------------------------------
![image](https://user-images.githubusercontent.com/20777145/126347379-dc0ab492-4547-4acf-a93f-c6237f38fd64.png)

Fast, light-weight JSON for all your needs. Works perfectly all the way from Unity 5.2 to Unity 2023 and 6. Completely stand-alone, nothing but C# for maximum compatibility and portability.


Does all the basic things. Create and modify JSON, parse strings to JSON and turn JSON objects to strings (compact or pretty), serialize objects to JSON and JSON back to objects. But also:


Made with Unity and easy usage in mind:
- You can follow content of JSON objects directly in Unity Editor when application is playing
- Complete inline C# documentation of all classes and methods
- Very informative exception messages for easy debugging


Safe:
- JSON objects can be set protected to prevent accidental modifying
- Strongly typed, you can't accidentally read values in wrong format
- Prevents creating circular JSON structures


Going the extra mile:
- Supports all different C# number types, but also numbers of any size outside long/double range
- No limits how deep JSON objects can be
- Debug IDs helps to track down exception sources even when stack trace is not available
- Multiple examples, also real-life data examples
- Keeps key/value pairs of JSON object in order
- API documentation also available online

------------------------------
INSTALLATION INSTRUCTIONS
------------------------------
- Open your unity package manager manifest (YourProject/Packages/manifest.json)

- Add a new entry...\
  "com.leguar.totaljson": "https://github.com/GambitGamesLLC/unity-plugin-totaljson.git?path=Assets/Plugins/Package",

- If you want to keep up to date with this repo, then you're done.
- If you want a specific version, add #v1.0.0 to the end of the URL (replace with the released version you want)

- Check the [Unity manual](https://docs.unity3d.com/Manual/upm-git.html#subfolder) on installing plugins from the subfolder of a Git repo for more info.
