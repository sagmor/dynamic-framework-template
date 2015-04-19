# Dynamic Framework Template

Template for building dynamic frameworks for iOS and Mac platforms

## Usage

To use this template, all you have to do is clone this repo and run it's rename script

```bash
# Choose a name
FRAMEWORK_NAME="AwessomeFrameworkProject"

# Clone this repo
git clone https://github.com/sagmor/dynamic-framework-template.git $FRAMEWORK_NAME
cd $FRAMEWORK_NAME

# Rename the template
script/rename $FRAMEWORK_NAME

# Bootstrap your new project
script/bootstrap

# Start Working on it
open $FRAMEWORK_NAME.xcworkspace
```

