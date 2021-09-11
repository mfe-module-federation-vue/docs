Start here and understand our project

# Architecture

## Root
> This is the entry point of the project, the `host` of the a architecture, know as app shell too.
> [Repo](https://github.com/mfe-module-federation-vue/root)

### Remotes Used
- Auth
- Products
- Profile
- Cart
- Design System

### Package
- dealful-package

_________________________________________________________

## Auth
> This is the authentication module, that deals and the only who knows the user state
> [Repo](https://github.com/mfe-module-federation-vue/auth)

### Exposes
*Components*
- Login
- Logout

*Service*
- UserTools

### Remotes Used
- Design System

### Package
- dealful-package


_________________________________________________________
## Products
> This is the module in charge of retrieving the product list and add it to the cart
> [Repo](https://github.com/mfe-module-federation-vue/products)

### Exposes
*Page*
- Products

### Remotes Used
- Design System

### Package
- dealful-package


_________________________________________________________
## Profile
> This is the module in charge of showing the user info, both in the user page and the user component
> [Repo](https://github.com/mfe-module-federation-vue/profile)

### Exposes
*Components*
- Profile

*Route*
- Profile Route (self invoke the FullProfile Page)


### Remotes Used
- Auth
- Design System

### Package
- dealful-package


_________________________________________________________
## Cart
> This is the module in charge of checkout, the cart
> [Repo](https://github.com/mfe-module-federation-vue/cart)

### Exposes
*Components*
- CartIcon

*Pages*
- Cart

 ### Remotes Used
- Design System

### Package
- dealful-package

_________________________________________________________
## Design System
> As the name indicates its the module in charge of componentization
> [Repo](https://github.com/mfe-module-federation-vue/design-system)


### Exposes
*Components*
- Inpuy
- Button
- UserPicture
- Vuetify `v-app` wrapper

*Files*
- Vuetify config


_________________________________________________________

## dealful-package 
> Dealful is a package to create deals for our mfes, it's in some sort of way the "contract" between the modules to the comunication be asure.
> [Repo](https://github.com/mfe-module-federation-vue/dealful-package)

