# Qodana <> AIR DEMO

## Run this before demo
```
git fetch origin

RUN="demo/run-$(date +%Y%m%d-%H%M%S)"

git switch -c "$RUN" origin/demo/seed
git push -u origin "$RUN"
```

## Step 2
Create a pull request in GitHub with:
Setting	Value
Base repository = Your private repository
Base branch = demo/base
Compare branch = Your new demo/run-* branch
Title	Qodana + Air Remediation Demo