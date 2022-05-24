# LimonJS
LimonJS JavaScript Library
# Docs
## asyncfor()
Makes A "For" Task In Background.
### Usage
asyncfor(Start,End,Step,ImportedVar,Function,Speed)

* Start => Integer
* End => Integer
* Step => Integer
* ImportedVar => Object
* Function => Function (Step, ImportedVar)
* Speed => Integer (1 Recomended)
## messag()
Shows A Message Box To User
### Usage
messag(msg,title,okbutton,nobutton,cncbutton,callback,top[?="10px"])

* msg => String (Message To Show)
* title => String
* okbutton => String (Text To Show In "Ok/Yes" Button)
* nobutton => Boolean (If True, It Adds A "Cancel,No" Button)
* cncbutton => String (Text To Show In "Cancel,No" Button)
* callback => Function (true=Ok/Yes, false=Canceş/No)
* top [OPTIONAL, Default = "10px"] => CSS Position
## setattrs
Set Attributes For Elements Got By `document.querySelectorAll` Or Array Contains HTML Elements
### Usage
setattrs(elems,attrname,val,add)

* elems => Array [Html Element]
* attrname => String (Attribute Name)
* val => String (Value To Set)
* add => Boolean (If True It Adds "val" To The Attribute)
## makecolorful()
Make Text Colorful That Made Out With "c" Tags
### Usage
makecolorful(elem,colors)

* elem => HTML Element
* Colors => Array [Css Colors]
## Image View
View A Image Fullscreen
### Usage
imageView(url)

* url => Image URL
