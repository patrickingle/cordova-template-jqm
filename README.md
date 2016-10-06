# cordova-template-jqm
A cordova template with jQuery Mobile. Learn more about templates at https://cordova.apache.org/docs/en/latest/guide/cli/template.html

# Creating a new cordova app using this template

From the command line, navigate to the directory you want the project to reside, then issue the command

cordova create hello com.example.hello HelloWorld --template https://github.com/patrickingle/cordova-template-jqm.git

# After creating a new project using this template

1. Ensure the file add-plugins.sh under the hooks path has executable permissions

2. Change to the project root folder: cd projectFolder

3. Issue the command: cordova platform ls, this command will pull some base plugins and add browser, ios, android and windows platforms
