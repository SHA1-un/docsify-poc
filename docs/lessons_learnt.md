# Lessons Learnt

## How to update CC runtime version

> ### Step 1:
You can use the find and replace functionality to update all the runtime flags in the package.json files.

> ### Step 2:
Check the package.json file for the following dependencies and devDependencies `@journeyapps/cloudcode` and `@journeyapps/cloudcode-build`  and update the version to the latest version number as well.

> ### Step 3:
Update the yarn.lock files for all the cloud code task that you have updated the details stated in step 2.

> ### Note:
If step 2 is not done the cloud code will still deploy fine but will fail to execute. It will also not trigger any roll bar when failing.

---

## Thing2
