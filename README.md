
🗒 Git & GitHub 🧾️
===================

🧷️ Why GitHub is important?

🔵 GitHub is a centralized platform. Centralized for developers all around the globe. A person can just host the repository created in Git to the whole world. Using this,
it increases the chances of better project development and in less time. GitHub provides you with the easiness of combining the changes and removes the headache of sharing the large code files. If GitHub is not there,
you will face a series of challenges in order to work together as a team.

First of all, the code needs to be shared among your teammates. A code file on a big project is heavy and will take a lot of resources. After the upload,
when your teammates will make the changes to the file, they still have to upload the complete file each and every time. This problem is not present when you use GitHub.
Just make the changes and push only the changes to the main code file. It will be fast and easy. As a project owner, you can track these changes quite easily on it.


🧷️ This Summary includes :

What is Git and Github ?
Why you must learn Git ?
Words you will hear
Important Notes
How to get start
Add / Reset / Commit Repository
How to Push Local Changes To Remote Repository
Everything about configuration
How to generate and test github public key
How to create repository from existing project
Everything about aliase
braching and merging
Mastering Stash
How to Restore / clean files
resetting the head
ignoring files and directories
tagging and releasing
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

➊ What is Git and Github ?

🎈 Git is distributed version control System

💊 ال git بيهندل ال versions بتاعتك
لو انت بتشتغل في house software او في أي شركة و عندكم project معين شغالين عليه و 
ال project دا بيطور مع الوقت سواء بتحلوا فيه مشاكل معينة او بتضيفوا فيه features جديدة 
او بتعملوا enhance للكود ف المراحل اللي انت بتمر بيها دي كلها اسمها


🎈 Git is free and open source

💊 أي tool بتشتغل بيها الزم تعرف هي بفلوس وال أل عشان تقرر قبل ما تتكلم عنها او تشتغل بيها 
هل هي محتاجة منك cost وال أل 
ال git عبارة عن free وsource



🎈 Github is source for projects and sources [Gitlab , BitBucket]

💊  Github عبارة عن website فيه source ال projects اللي انت بتشوفها 
الشركات كلها بتحط فيه ال source بتاع ال projects بتاعتهم سواء الحاجات ال open
sourceاو المكتبات اللي انت بتشتغل عليها هتالقي ال project بتاعها موجود على github
ممكن ت contribute عليه و تحط فيه تعديالت و كدا
في مواقع كتير زي gitlab و bitbucket بتأدي نفس وظيفة



 Github simplify using Git

💊 ال github بيسهل استخدام ال git بطريقة بسيطة و سهلة و بيديلك شوية إمكانيات كويسة زي 
issue trackerال


🎈  --> you can use Git without Github
    --> Git has GUI

💊 ال git ليه واجهة جرافيكية يعني تقدر تستخدمه بال mouse عادي 
حتى موقع Github ليه برنامج اسمه desktop github تقدر تعمل فيه كل القصة دي بال
mouse عادي

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

➋ Why you must learn Git ?

🎈  Devs Contribute to the same project

💊 مع ال Git كلنا بن contribute لبروجيكت واحد مفيش حد منفصل او شغال لوحده




🎈 you can revert changes

💊 تقدر ت changes revert و تعرف مين عملها و تقدر تلغيها
-- you can collaborate to fix issues
-- you can collaborate to create new features
-- you can solve conflicts
لو واحد خد function معينة و عدل عليها و ال function دي فيها عندي اختالف ف بسهولة 
شديدة بيجيب االتنين و يجيب مقارنة مبينهم و نشوف ال conflict فين و تعدل و ترفع و هتالقي 
الشخص التاني ياخد النسخة السليمة او العكس
-- you can organize features

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

➌ Words you will hear 

🎈 Repository
💊هو المستود ع اللي بتحط فيه اكواد ال project بتاعك كاملة لو انت مثال عندك projects two
شغال عليهم في الشركة ف المفروض يكون عندك اتنينrepository
ال repository بيختصروها لr


🎈 Branch
💊 يعني قسم او فرع
ال branch في عالم ال Git فرع من ال repo ممكن تاخد branch عشان تعمل تعديل معين 
بس في البروجيكت التعديل ممكن يكون إضافة صغيرة مطلوبة منك او ممكن تاخده تحل بيه
bugطبعا دي آلية من شركة لشركة لكن دا األساس


🎈 Local Repo
💊 ال local هو الحاجة بتاعتك انت اللي شغال عليها دلوقتي على ال PC بتاعك 


🎈 Remote Repo
💊 ال remote هنا ممكن يكون موقع ال github او ال bitbucket او ال gitlab او السيرفر بتاع 
الشركة


🎈 Commit (snapshot or checkpoint in your local Repo)
💊 لما انت تعمل تعديل معين او خلصت feature معينة او حليت ال bug بتعملcommit
ال commit دا بيعمل checkpoint للكود في ال repo local بتاعك


🎈 Clone [from local to remote]
💊 Cloneيعني استنساخ بستنسخ ال repo اما من ال local او الremote
ال local ممكن تستنسخ منه بس في location تاني


🎈 push [upload local changes to remote]
💊 ال push بترفع منه بت upload ال changes بتاعتك لل repo re


🎈 pull [you pull changes from remote repo to your local] 
💊 ال pull بتسحب التعديالت من ال repo remote لل repo local بتاعتك

🎈 pull request [tell other about your changes to pull it from local to remote]
💊 ال request pull انت عملت تعديل معين ف بتقول للي معاك في تعديل عايزك تاخده من ال
localلل remote عندك


🎈README
💊 بنكتب فيه أي حاجة تخص المشروع أي notes عاوز تحطها في المشروع أي حاجة محتاج 
الشخص لما يجي يدخل على المشروع يعمل أي حاجة يشوف مثال ال steps دي يعملها
ال README مهم جدا بيكون فيه الحاجات اللي ممكن تخلي الناس ميغلطوش في حاجة مثال 
انت بتعملها 
امتداده md و دي markdown بتكتب بيها زي ال text كدا بس بتنثقه
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

➌ Important Notes 

➻ Create Repository for every project
➻ Create a new branch for every feature or enhancement
➻ No need to connect to remote repo when working
➻ Anyone can push and pull depend on permissions

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

➍ Getting Started

you can create a repository with either of the following 
commands :
❖ git clone < your repository URL >
 Copies a remote repository into your current directory
❖ git init
 Creates a new empty repo in your current directory
------------------------------------------------------------------------------------------------------------------------------------------------------------------------

➎ Add / Reset / Commit

show status :
❖ git status
 Lists changes in working directory and stages files
status Git بيوريني الحالة او ايه اللي ناقص او ايه اللي عندك في ال directory working يعني بيفهمني 
ايه اللي بيحصل 

add files :
❖ git add < file1 > < file2 >
 Adds < file1 > and < file2 > to the staging area
❖ git add *.extention ( git add * .py )
 Adds all python files in the current directory to the staging area
❖ git add *
 Adds all files to the staging area

unstage:
❖ git reset head < file >
بيرجع ال file من ال stage اللي مش عاوز اعمله track عاوز اسيبه
❖ git reset
 removes all files from staging area (opposite of git add)
❖ git reset < filename >
 removes < filename > from staging area


commit changes :
❖ git commit 
 Records everything in the staging area to your repository. The default text 
editor will prompt you far a commit message
❖ git commit -m “ commit message “
 Records everything in the staging area to your repository with the commit 
message “ commit message “
❖ git commit –amend
 Modify last commit instead of creating a new one useful for fixing small 
mistakes

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

➏ Push Local Changes To Remote Repository
 
show branches:
❖ git branch
 list branches
❖ git branch < branch-name >
 create new branch < branch-name >
❖ git remote -v
 git remote repository

push changes :
❖ git push < Repo > < Branch >
 incorporates changes from local repo into < repo > < branch >
❖ git push
 incorporates changes from local repo into ‘origin’


pull changes from remote repository :
❖ git pull 
 incorporates changes from ‘origin’ into local repo
❖ git pull < repo > < branch >
 incorporates changes from < repo > < branch > into local repo

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
➐  Everything about configuration

show all configurations :
❖ git help config
هيفتح ال manual بتاع ال git اللي فيه حاجات ممكن متكونش مكتوبة في ال file اللي عندي 
❖ git config -l
هيجبلي ال configuration اللي عندي 

 show user email :
❖ git config --global user.email

change user email :
❖ git config –global user.email “ your github email here “

edit configuration :
❖ git config --global –edit
❖ git config --global credential -helper store
 will store your login details next time they are entered, saving you from 
having to enter them again

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
➑ generate and test github public key 

Generate key :
❖ ssh -keygen -t rsa -b 4096 -c “ your github email here “

Git key to copy :
❖ cat ~/ .ssh/ id_rsa.pub
same command example in windows " change shorouk with 
your username " :
❖ cat c:\users\shorouk\.ssh\id_rsa.pub

test key and connection :
❖ ssh -T git@github.com

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
➒ create repository from existing project

create new directory :
❖ mkdir “ your directory name here “

initialize empty git repository :
❖ git init

create empty file :
❖ touch “ your file name here “

show status :
❖ git status

add files :
❖ git add < file > < file >

commit file :
❖ git commit -m “ your commit message here”

add repository :
❖ git remote add origin “ssh repository URL”

example :
❖ git remote add origin “ git@github.com: shorouk/course.git”

push data :
❖ git push -u origin master
ال u -بتخليك تعتبر انك بتعمل pull و بعدين push االتنين متتال يين

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

❿ Everything about aliases

make alias for command " status " :
❖ git config --global alias.st status

show alias content :
❖ git config --global alias.st

test "status" command :
❖ git st

make alias for command " branch " :
❖ git config --global alias.br branch

show alias content :
❖ git config --global alias.br

test " branch " command :
❖ git br

make alias for command " commit -m " :
❖ git config --global alias.cm “ commit -m “

show alias content :
❖ git config --global alias.cm

test " branch " command :
❖ git cm

show all edits :
❖ git config --global –edit

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☼ braching and merging

show branches :
❖ git branch

switch to branch :
❖ git checkout “ branch name “
 switch to editing branch < branch-name >

delete branch :
❖ git branch -d < branch name >
 d -بيعملك حاجة اسمها delete save بيخلي ال git ي check هل ال branch بتاع كدا فيه تعديالت معينة 
متعملهاش merge و في الحالة دي مبيرضاش يحذف 
 D -بيحذفه حتى لو في تعديالت 

move / rename branch :
❖ git branch -m “ new branch name “

merge branch with current branch :
❖ git merge “ Branch name you need to merge “
 merge < branch name > into current branch

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☼ Mastering Stash

Create text file with " hello world " string inside it :
❖ echo “ hello world “ > about readme.txt

save work to stash :
❖ git stash

list items in stash :
❖ git stash list

Get work from stash :
❖ git stash pop
stash بتخزن فيه الملفات بتاعتك زي الصندوق اللي بحتفظ فيه حاجة لحد ما اجى استخدمها
 Pop بيجيب الملفات و يعمل drop لل stash

save work to stash with description :
❖ git stash save “ description here “

get specific stash :
❖ git stash pop stash@{1}

delete stash :
❖ git stash drop stash@{2}

show latest added stash content :
❖ git stash show

show specific stash content :
❖ git stash show stash@{1}

empty the stash :
❖ git stash clear

get work from stash without delete it :
❖ git stash apply
 apply بياخد التعديالت زي ما هي و يسيبلك ال stash في مكانه

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☼ Restore / clean

restore staged files :
❖ git restore --staged “ file name here “
لو محتاج اشيل فايل من الarea stage
❖ git restore --staged *

show files that will be cleaned :
❖ git clean -n

remove un needed files :
❖ git clean -f

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☼ resetting the head

ال reset بيخليك تحذف ال commit اللي انت مش محتاجها 
بيخليك تحذف مجموعة ال commits اللي انت بتكون عاوز تلغيها او فيها مشاكل ايا كان 

show log file :
❖ git log
 prints commit history of repo
❖ git log < file name >
 prints commit history of < file name >

reset head :
❖ git reset --hard " commit hash here "

push edits from local to remote with force flag :
❖ git push origin main –force
لما بخلي ال head عند commit معين وبعدها اعمل reset ف كل ال commits اللي بعده بتتمسح

------------------------------------------------------------------------------------------------------------------------------------------------------------------------
☼ ignoring files and directories

ازاي نتجاهل ملفات معينة عشان متترفعش للمشروع بتاعنا 
create gitignore file : 
❖ touch -gitignore

ملف ال gitignore هو الملف اللي هيحتوي على الملفات اللي عاوزين نتجاهلها و متترفعش مع ال project
push file that is ignored :
❖ git add -f < file name >
❖ git add --force < filename >

لما يبقى في file في ال gitignored و عاوز اعمله push
example for gitignored file content :
*.log
! vip.log
node_packs/
text.txt

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

☼ tagging and releasing
ال tag هي حاجة بتخليك تعلم على جزء معين من المشروع بتاعك في حقبة زمانية معينة 
بيستخدموها دلوقتي لالصدارات في المشروع بتاعك 
ميزة ال tag بتخليك تحمل الجزء االول لوحده و الجزء التاني لوحده و هكذا 
show all tags :
❖ git tag

add new lightweight tag :
❖ git tag " version name or tag name here "

ال tag lightweight git هي tag مرتبطة بال commit حتى المعلومات او ال message اللي انت كتبتها 
في ال commit
add new annotated tag :
❖ git tag -a " version name or tag name here " -m " description or 
message "
ال tag annotated ملهاش عالقة بال commit انت بنفسك اللي هتكتب ال description الخاص بيها 
push tag to remote :
❖ git push origin " tag name here "
list all tags starting with v1 : 
❖ git tag -1 "v1.*"
delete tag :
❖ git tag -d " version name or tag name here "
delete tag from remote :
❖ git push origin --delete "version name or tag name here"

------------------------------------------------------------------------------------------------------------------------------------------------------------------------

☛ Waled Saied  
