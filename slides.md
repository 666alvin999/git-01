<!-- slides.md -->

# GitHub Bootcamp

---

## How to initialise a new repository

```console
git init
```
<p>&nbsp;</p>

if you are in an app with node used, dont forget to add

```console
echo 'node_modules' > .gitignore
```

---

## How to review changes

```console
git diff
```

allows you to see all the changes in all the files you modified

---

## How to commit changes

3 steps:

```console
gss
gaa
gcmsg '<commit-message>'
```

- gss (git status -s): allows you to see which file you modified
- gaa (git add --all): add all the modified files to the stage
- gcmsg (git commit -m): create a new version of your project with all the modifications you've made

---

## How to create a new branch

```console
gb <branch-name>
```

gb === git branch

---

## Merge a branch on main

```console
git checkout master
gm -m '<merge-message>' <feature-branch>
```

gm === git merge
-m allows you to add a merge message

---

## Delete a branch

```console
gbd <branch-to-delete>
```

gbd === git branch -delete

---

## Pushing changes to remote

Once you committed your changes, run the command

```console
gpsup
```
gpsup === git pull -u origin main

---

## Pulling changes from remote

```console
gl
```
gl === git pull

---

## Text

lorem ipsum

---

## Lists

- Lorem
  - ipsum
- Hello
  - World

---

## Images

![Rick Roll](https://dogemuchwow.com/wp-content/uploads/2019/09/cursed-cat-image-163325.jpg)

--- 

## Headers and Quotes
### Chipi chipi
#### Chapa chapa

> Dubi dubi daba daba

---

## Code

```java
class Car {
    private int doors;
    private int horses;
    private String engine;
    
    public Car() {
        this.doors = 0;
        this.horses = 0;
        this.engine = null;
    }
}
```

---

## Extras

$15... more extra to test git cz
aaaaaaaaa

---

## How to automate issue closing

---

# How to apply commit

---

## How to fix last commit message
