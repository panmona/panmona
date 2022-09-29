<h2> Hey, I'm Mona! 🌺 </h2>
<img align='right' src="https://media3.giphy.com/media/Z9WRoncIw8RYBLJ0FB/giphy.gif?cid=ecf05e47k92frft9hvl705cplk154nfh8n44p8go9fv7uvhc&rid=giphy.gif&ct=s" width="200">
<p><em>- Software Engineer at <a href="http://www.vlot.ch">vlot</a> <br>
   - Computer Science Student at <a href="https://www.ost.ch">Eastern University of Applied Sciences</a>
</em></p>


#### <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="40"> A little bit more about me...  

```fsharp
let mona = {
  Name = "Mona Celeste Panchaud"
  Pronouns = [ She; Her ]
  Code = [ ``F#``; CSS; LaTeX; JavaScript ]
  Tools = [ Rider; React; Fable; Feliz; Elmish; Expecto ]
  OutsideOfCode = [ "🪡🧵"; "🏊‍♀️"; "📚"; "🚴‍♀️"; "⛰️";  ]
}
```


If you're interested in the types that make the above F# code compile, see below.
        
<details>
<summary>F# Types</summary>

```fsharp
type Pronoun = She | Her | He | Him | They | Them

type Language = ``F#`` | CSS | JavaScript | LaTeX

type Tool = Rider | React | Fable | Feliz | Elmish | Expecto

type Person = {
  Name: string
  Pronouns: Pronoun list
  Code: Language list
  Tools: Tool list
  OutsideOfCode: string list
}
```

</details>
