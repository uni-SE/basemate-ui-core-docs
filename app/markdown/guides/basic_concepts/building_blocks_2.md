### Component

If you think of an UI, a small component may be a simple button. A bigger component may
use three other components, including an image-component, a text-component and this
button-component to display a product-image, -description and a "more details" button.

A component is the smallest UI-Element and can consist of other components

### Page

20 of these product-components should be displayed on a specific page of your Web-App.
A page therefore defines, that 20 product-components should be used and how they should
be aligned to each other.

A page composes multiple components in order to display the main content

### App

Usually a page should be wrapped in a layout. A layout may define a navigation-menu,
header and footer for example. In basemate, a layout is defined in an app. Multiple
pages belong to one basemate app, which can perform dynamic transitions
between its pages. A Rails Application may host multiple basemate apps: One could
be the Online-Shop-App, displaying products on multiple pages. The other could be
an Backoffice-App managing all kind of data and processes.

A basemate app manages multiple pages in order to fullfill one specific purpose of your organization
