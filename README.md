# 0 Project

---

> This is the first repository project, you can found it here: 
> [`github.com/PeshiyXod/0-Project`](https://github.com/PeshiyXod/0-Project "Link to 0 Project")

```mermaid
graph TD;
  untracked         -- "git add"    --> staged;
  staged            -- "git commit" --> tracked/comitted;
  tracked/comitted  -- "modified"   --> tracked/modified;
  tracked/modified  -- "git add"    --> staged;
  tracked/comitted  -- "git push"   --> uploaded;
```