# Roll Ability Scores

Just copy and paste the below text into the chat window in Roll20 (the line break after the `(!` is required!), and your players will be given abutton to roll their ability scores using 4d6, drop lowest. Each ability score is rolled with the formula `[[4d6dl1cf<0cs>7]]` so that 1s and 6s aren't highlighted.

```
&{template:npcaction} {{rname=Roll Ability Scores}}{{description=

[Good luck...](! 
&#38;&#123;template:default&#125;&#123;&#123;name=Ability Score Results&#125;&#125;&#123;&#123;Ability Score 1=&#91;&#91;4d6dl1cf&lt;0cs&gt;7&#93;&#93;&#125;&#125;&#123;&#123;Ability Score 2=&#91;&#91;4d6dl1cf&lt;0cs&gt;7&#93;&#93;&#125;&#125;&#123;&#123;Ability Score 3=&#91;&#91;4d6dl1cf&lt;0cs&gt;7&#93;&#93;&#125;&#125;&#123;&#123;Ability Score 4=&#91;&#91;4d6dl1cf&lt;0cs&gt;7&#93;&#93;&#125;&#125;&#123;&#123;Ability Score 5=&#91;&#91;4d6dl1cf&lt;0cs&gt;7&#93;&#93;&#125;&#125;&#123;&#123;Ability Score 6=&#91;&#91;4d6dl1cf&lt;0cs&gt;7&#93;&#93;&#125;&#125;)}}
```
