# Tip Calculator

Github and Markdowns

* [Git cheatsheet](https://www.git-tower.com/blog/git-cheat-sheet/)
* [Markdown sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

This application will add tax based on a State and calculate a tip based on a percentage

This uses a locally downloaded version of angularjs, (angular.js)


 

```
            <p>

                Cost: <input type="text" ng-model="cc.cost" placeholder="cost" /><br/>

                State: <select ng-model="cc.state" ng-options="s.name for s in cc.state_options"></select><br>
                
                Tip: <select ng-model="cc.tipping" ng-options="s.name for s in cc.tipping_options"></select>

            </p>
```