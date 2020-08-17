## Git հրամաններ
### Այստեղ այն հրամաններն են որոնք օգտագործում ենք

git init - Ստեղծում է նոր repository

git status - Ցույց է տալիս ներկայիս իրավիճակը repository-ում

git add <file> - Ավելացնում է ֆայլը commit արվող ֆայլերի ցուցակում

git rm --cached <file> - Հանում է ֆայլը commit արվող ֆայլերի ցուցակից

git commit - Ստեղծում է commit գրանցված ֆայլերով

git diff <file> - Ցույց է տալիս ֆայլի մեջ եղած փոփոխությունները

git checkout <commit-code> - Գնում է այդ commit-ի տարբերակի վրա (այսինքն ֆայլը բերում է այն վիճակի ինչպիսին էին այդ commit-ի ժամանակ)
  
git checkout -b <new-branch-name> - Ստեղծում է նոր branch

git remote add origin <github-repo-address> - Կցում է Github-ի repository-ին

git push origin <branch-name> - Ուղարկում է մեր փոփոխությունները Github-ի repository-ին

git pull - Քաշում է փոփոխությունները Github-ի repository-ից ու կիրառում մեր լոկալ repository-ում

git clone - Կլոնավորում է Github-ի repository-ին մեր համակագչի վրա

git branch -D <branch-name> - Ջնջում է նշված branch-ը
