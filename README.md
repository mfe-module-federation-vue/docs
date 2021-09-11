# docs
Start here and understand our project

## Architecture

### Root
> [Repo](https://github.com/mfe-module-federation-vue/root)

#### Remotes Used
- Auth
- Products
- Profile
- Cart
- Design System

#### Package
- dealful-package

### Auth
> [Repo](https://github.com/mfe-module-federation-vue/auth)

#### Exposes
**Components**
- Login
- Logout

**Service**
- UserTools

#### Remotes Used
- Design System

#### Package
- dealful-package


### Products
> [Repo](https://github.com/mfe-module-federation-vue/products)

#### Exposes
**Page**
- Products

#### Remotes Used
- Design System

#### Package
- dealful-package


### Profile
> [Repo](https://github.com/mfe-module-federation-vue/profile)

#### Exposes
**Components**
- Profile

**Route**
- Profile Route (self invoke the FullProfile Page)


#### Remotes Used
- Auth
- Design System

#### Package
- dealful-package


### Cart
> [Repo](https://github.com/mfe-module-federation-vue/cart)

#### Exposes
**Components**
- CartIcon

**Pages**
- Cart

 #### Remotes Used
- Design System

#### Package
- dealful-package


### dealful-package
> [Repo](https://github.com/mfe-module-federation-vue/dealful-package)
 
Dealful is a package to create deals for our mfes, it's in some sort of way the "contract" between the modules to the comunication be asure.



### Design System
> [Repo](https://github.com/mfe-module-federation-vue/design-system)


#### Exposes
**Components**
- Inpuy
- Button
- UserPicture
- Vuetify `v-app` wrapper

**FIles**
- Vuetify config
