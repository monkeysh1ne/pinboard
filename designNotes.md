gems
====

devise
HAML
bootstrap-sass
simple_form
paperclip






syntax notes
============

rails g model Pin title:string description:text

resources : pins

params.require(:pin).permit(:title, :description)

rails g devise User
