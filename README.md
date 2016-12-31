# smithjw-recipes
[smithjw's](https://twitter.com/smithjw) AutoPkg recipes

In order for any of the `-selfservice` recipes to work properly, you will need to download [@homebysix's](https://twitter.com/homebysix) `PolicyTemplate-selfservice.xml` file from his [Auto-Update-Magic repo](https://github.com/homebysix/auto-update-magic/). 

The reason I haven't included this file in my repo is to ensure that anyone who wan't to enable these recipes understands the risks associated with pushing software update via AutoPkg directly into Self Service bypassing any testing. 

⚠️⚠️**This is a dangerous action and I would caution you from enabling this unless you are aware of the risks involved.**⚠️⚠️

I would also recommend reading [@homebysix's original exersice](https://github.com/homebysix/auto-update-magic#exercise-6c-sending-software-directly-to-self-service-policies) that documents this process. Actually, set aside a couple hours, grab yourself a 🍺/🍷 , and read the [whole thing](https://github.com/homebysix/auto-update-magic#overview). A lot of thought and effort has gone into Auto-Update-Magic and I believe it makes life significantly easier for Mac Admins everywhere.

## Enabling -selfservice Recipes

Now for the fun stuff. In order to make these recipes work, you'll need to do the following:

1. Download [PolicyTemplate-selfservice.xml](https://github.com/homebysix/auto-update-magic/blob/master/Exercise6c/PolicyTemplate-selfservice.xml)
2. Place `PolicyTemplate-selfservice.xml` at `~/Library/AutoPkg/PolicyTemplate-selfservice.xml`
3. Run `-selfservice` recipes

---

Need to add in Apache licence and reference to the template files from https://github.com/homebysix/auto-update-magic/ that I've made use of to implement Auto-updating Apps in Self Service
