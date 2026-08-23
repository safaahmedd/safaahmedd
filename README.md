
<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=safa.py&fontSize=60&fontColor=f093fb&fontAlignY=45&animation=fadeIn" width="100%"/>
</div>

```python
"""
safa.py
a second-year data science student who never learned to stay in one lane.
run this file if you want the honest version, not the LinkedIn version.
"""

class Safa:
    def __init__(self):
        self.location = "Islamabad, PK"
        self.studying = "Data Science @ FAST NUCES"
        self.currently = "interning @ Jazz — chapter still unwritten"
        self.believes = "the best solutions live in the overlap, not in one lane"

    def where_ive_been(self):
        return {
            "🏛️  U.S. Embassy Islamabad": "Public Diplomacy Intern — ran cultural "
                "exchange programs, prototyped the Lincoln Corners website, sat in "
                "rooms with actual diplomats and tried not to look nervous",

            "🏆  Uber Global Hackathon": "regional finalist, out of 730+ teams — "
                "still don't fully believe this one",

            "🧠  this one summer": "Deloitte job simulation + an agentic AI workshop "
                "+ a U.S. Embassy AI Impact camp, back to back — turns out 'break "
                "from my degree' meant 'more AI, just the hands-on kind'",

            "🎨  Google UX Design": "because how something feels matters as much "
                "as whether it works",
        }

    def side_quests(self):
        # things I built because I wanted to, not because I had to
        return [
            "taught two AI agents (Minimax vs. Expectimax) to disagree over UNO",
            "rebuilt Xonix in C++/SFML — my first real hello to a graphics library",
            "started beadwork after years of 'one day' — turns out my hands like "
                "making things that aren't code too",
        ]

    def known_bugs(self):
        # honesty > polish
        return [
            "goes straight to the cinema after anything mentally overwhelming, "
                "no exceptions, no patch planned",
            "promises herself a break, ships more work instead",
        ]


if __name__ == "__main__":
    me = Safa()
    print(f"📍 {me.location}")
    print(f"🎓 {me.studying}")
    print(f"⚡ {me.currently}")
    print(f"💭 {me.believes}\n")

    for place, note in me.where_ive_been().items():
        print(f"{place}\n   → {note}\n")
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f0c29,50:302b63,100:24243e&height=2&width=1000" width="100%"/>
</div>

## `>>> import projects`

<table>
<tr>
<td width="50%" valign="top">

```python
# uno_search_agents.py
class MinimaxPlayer:
    """trusts no one. plans for
    the worst case, always."""

class ExpectimaxPlayer:
    """reads the room. bets on
    what's likely, not certain."""

# they argue over UNO.
# it's more entertaining than
# it has any right to be.
```
**[→ view repo](https://github.com/safaahmedd/uno-using-search)**
`Python` `Minimax` `Expectimax`

</td>
<td width="50%" valign="top">

```cpp
// xonix, rebuilt
// started: a bare game loop
// ended: menus, difficulty
//   levels, a scoreboard,
//   and a 2-player mode
//   that's trying its best

// first real hello to a
// graphics library. the
// moment "object-oriented"
// stopped being a buzzword.
```
**[→ view repo](https://github.com/safaahmedd/xonix-game-cpp)**
`C++` `SFML` `CMake`

</td>
</tr>
</table>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f0c29,50:302b63,100:24243e&height=2&width=1000" width="100%"/>
</div>

## `>>> print(me.stack)`

<div align="center">
<img src="https://skillicons.dev/icons?i=python,cpp,html,css,js,figma&theme=dark" /><br><br>
<img src="https://img.shields.io/badge/-Data%20Science-000000?style=flat-square&labelColor=000000&color=f093fb" />
<img src="https://img.shields.io/badge/-Generative%20AI-000000?style=flat-square&labelColor=000000&color=764ba2" />
<img src="https://img.shields.io/badge/-UX%20Design-000000?style=flat-square&labelColor=000000&color=fda085" />
<img src="https://img.shields.io/badge/-Public%20Speaking-000000?style=flat-square&labelColor=000000&color=96e6a1" />
<img src="https://img.shields.io/badge/-Creative%20Writing-000000?style=flat-square&labelColor=000000&color=fbc2eb" />
</div>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f0c29,50:302b63,100:24243e&height=2&width=1000" width="100%"/>
</div>

## `>>> me.stats()`

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=safaahmedd&show_icons=true&theme=tokyonight&hide_border=true&bg_color=00000000&title_color=f093fb&icon_color=fda085&text_color=c9d1d9" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=safaahmedd&theme=tokyonight&hide_border=true&background=00000000&ring=f093fb&fire=fda085&currStreakLabel=f093fb" width="48%" />
</div>

<div align="center">
<img src="https://komarev.com/ghpvc/?username=safaahmedd&style=flat-square&color=764ba2&label=profile+views" />
<a href="https://www.linkedin.com/in/safaahmed1"><img src="https://img.shields.io/badge/-linkedin/safaahmed1-000000?style=flat-square&logo=linkedin&logoColor=white&color=0A66C2" /></a>
</div>

```bash
$ safa --status
> still compiling. no errors yet. looking for the next thing worth building.
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%"/>
</div>
