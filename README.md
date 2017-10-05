
### This is template project for JuJaLabs.

## Some additional features:
 - Add mongodb to travis build
    * Add `mongodb` to travis service section
    * Add before script section and add this line   `mongo <db_name> --eval 'db.createUser({user:"root", pwd:"root", roles:[{role:"dbAdmin", db:"<db_name>"}]});'`
