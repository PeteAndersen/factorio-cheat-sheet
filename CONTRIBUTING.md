# To contribute
Make a new branch and follow the belt-thoughput example
* Make a new json data in assets/data
* Make a new component in src/app/views/cheat-sheets (make sure to add to the components in the index.ts and app.module.ts)
* Call the DataService.getCheatSheetData from src/app/services/data.service in the new component
* Use the src/app/shared/cheat-sheet template along with data in the component html file to customize the presentation

When done
* Run `npm run build`
* If successful build, then commit and push your changes.
* Create a Pull Request
