# NPP-CEF-Highlighting
A small self-made CEF User-Defined Language for Notepad++ to provide highlighting for common CEF log formats typically used in ArcSight.

This was made for use in darkmode. Haven't tested it on lightmode (I enjoy having vision).

Due to the nature of CEF logs parsing multiple types of logs from different logging formats from different sources, it is high likely that this will not cover all the types of logs you throw at it.
I slowly over time added multiple words that are commonly used in my case.
Therefore, if you notice any inconsistencies, you are very welcome to pull request so they can be added.
- Red = Important Fields
- Bold Blue = usually means action taken by an "IPS".

# Quick Setup
1) Open Notepad++
2) Head over to Language tab
3) Select "User Defined Language", then "Define your language..."
4) Hit "Import..."
5) Select the provided `.xml`
6) Restart Notepad++ and your done

Now just go to Language tab and choose "CEF Logs"
