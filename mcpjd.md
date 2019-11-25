## Magento 2 Certified Professional JavaScript Developer

### Introduction

This exam will validate the skills and knowledge needed to develop new JavaScript modules and customize existing ones. It will verify whether the developer understands the core Magento JavaScript framework, is able to use its components in the correct way, and understands best practices for customizing existing components and adding new ones. The exam pays particular attention to UI components, and will validate whether the developer understands their purpose, area of application, architecture, and lifecycle. This includes not only the in-browser JavaScript framework, but also the related server-side configuration for layout, customer data sections, and adminhtml UI components. This exam is for a JavaScript developer with broad experience in customizing Magento JavaScript for at least 1 year.
The test is built for the 2.2.x version of Magento Commerce and Magento Open Source.

Supporting Magento U course:
➢ JavaScript Development in Magento 2 (Instructor-Led)

This exam consists primarily of scenario-based questions in a multiple-choice format. Sample questions are included at the end of this guide.
Test time: 90 minutes. Passing score: 63% or above, 60 questions. Available to take remotely or at a test center.

### <a name="top"> Exam topics and the percentage covered in the test.</a>
  - [1. Technology Stack 20%](#1)
  - [2. Magento JavaScript Basics 25%](#2)
  - [3. Magento Core JavaScript Library 19%](#3)
  - [4. UI Components 24%](#4)
  - [5. Checkout 12%](#5)

## Topics and Objectives

### <a name="1">1 Technology Stack 20%</a> [Go to Top](#top)
#### 1.1 Demonstrate understanding of RequireJS
[alanstorm](https://alanstorm.com/magento_2_and_requirejs/), [belvg](https://belvg.com/blog/how-to-use-jquery-and-requirejs-in-magento-2-javascript-solutions.html)

##### Describe the RequireJS framework and its approach to JavaScript module organization
- What is the main purpose of the RequireJS framework?
- What are the pros and cons of the AMD approach to JavaScript file organization?
- Which capabilities does RequireJS provide to create and customize JavaScript modules?
##### Demonstrate the ability to use requirejs-config.js files in the development process
- What is a requirejs-config.js file?
- In which cases it is necessary to add configurations to it?
- What tools does it provide?
- What are global callbacks?
- How can mappings be used?
https://requirejs.org/docs/api.html#config-callback
##### Demonstrate the ability to use RequireJS plugins
- What are RequireJS plugins?
- What are the text and domReady plugins used for?

#### 1.2 Demonstrate understanding of UnderscoreJS
[veritstudio](https://veritstudio.com/blog/how-to-add-underscore-js-template-in-magento-2/), [codilar](https://www.codilar.com/blog/underscorejs/), [belvg](https://belvg.com/blog/one-more-magento-2-javascript-certified-developer-at-belvg.html)
##### Demonstrate understanding of underscore utility functions
- What are the benefits of using the underscore library versus native JavaScript?
##### Use underscore templates in customizations
- Describe how underscore templates are used.
- What are the pros and cons of using underscore templates?
- Describe how underscore templates are used in Magento together with the text RequireJS plugin.

#### 1.3 Demonstrate understanding of jQuery UI widgets
[belvg](https://belvg.com/blog/how-to-use-jquery-and-requirejs-in-magento-2-javascript-solutions.html), [jason](https://jason.codes/2019/06/magento-2-create-jquery-ui-widget/), [devdocs](https://devdocs.magento.com/guides/v2.3/coding-standards/code-standard-jquery-widgets.html), [devdocs](https://devdocs.magento.com/guides/v2.3/javascript-dev-guide/widgets/jquery-widgets-about.html)

##### Demonstrate understanding of the jQuery framework and its role in the Magento JavaScript framework
- What is a jQuery library?
- What different components does it have (jQuery UI, jQuery events and so on)?
- How does Magento use it?

#### 1.4 Demonstrate understanding of KnockoutJS
[devdocs](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/concepts/knockout-bindings.html), [codilar](https://www.codilar.com/blog/knockoutjs-in-magento-2/), [magestore](https://www.magestore.com/magento-2-tutorial/how-to-write-a-page-using-magento-2-knockout-js/), [belvg](https://belvg.com/blog/what-is-knockout-js-framework.html), [rohanhapani](https://www.rohanhapani.com/how-to-use-knockout-js-in-magento-2/)

##### Describe key KnockoutJS concepts
- Describe the architecture of the Knockout library: MVVC concept, observables, bindings.
##### Demonstrate understanding of knockout templates
- What is the main concept of knockout templates?
- What are the pros and cons of knockout templates?
- Compare knockout templates with underscore JavaScript templates.
##### Demonstrate understanding of the knockout-es5 library

## <a name="2">2 Magento JavaScript Basics  25%</a> [Go to Top](#top)

#### 2.1 Demonstrate understanding of the modular structure of Magento
[devdocs1](https://devdocs.magento.com/guides/v2.3/javascript-dev-guide/javascript/js-resources.html), [devdocs2](https://devdocs.magento.com/videos/fundamentals/add-a-javascript-module/)

##### Demonstrate understanding of the JavaScript file organization in Magento
- What file structure is used to organize JavaScript modules?
- Where does Magento locate a module’s JavaScript file?
- Where does Magento store the JavaScript library?
##### Describe how static content is organized in Magento
- How does Magento expose a module's static content to the web requests?
- What are the different ways to deploy static content?
#### 2.2 Describe how to use JavaScript modules in Magento
[devdocs](https://devdocs.magento.com/videos/fundamentals/add-a-javascript-module/), [belvg](https://belvg.com/blog/utilizing-javascript-component-in-magento-2.html), [firebearstudio](https://firebearstudio.com/blog/magento-2-javascript.html), [webkul](https://webkul.com/blog/include-use-custom-js-file-require-js-magento2/), [jamersan](https://jamersan.com/introduction-javascript-magento-2/)

##### Use requirejs-config.js files to create JavaScript customizations
- How do you ensure that a module will be executed before other modules?
- How can an alias for a module be declared?
- What is the purpose of requirejs-config.js callbacks?
##### Describe different types of Magento JavaScript modules
- Plain modules
- jQuery UI widgets
- UiComponents
#### 2.3 Demonstrate ability to execute JavaScript modules
[alanstorm](https://alanstorm.com/magento_2_javascript_init_scripts/), [toweringmedia](https://toweringmedia.com/blog/javascript-init-scripts-magento2/), [makandracards](https://makandracards.com/vasan/59776-magento-2-tips-how-to-use-javascript-in-magento), [stackexchange](https://magento.stackexchange.com/questions/159427/magento-2-run-execute-javascript-after-knockoutjs-has-rendered-all-elements?rq=1), [inchoo](https://inchoo.net/magento-2/custom-javascript-in-magento-2-with-requirejs/), [belvg](https://belvg.com/blog/how-to-use-jquery-and-requirejs-in-magento-2-javascript-solutions.html)

##### Demonstrate the ability to use the data-mage-init attribute to run JavaScript modules
- What is the purpose and syntax of the data-mage-init attribute?
- How is it used to execute JavaScript modules?
##### Demonstrate the ability to use text/x-magento-init scripts to execute JavaScript modules
- What is the purpose and syntax of the text/x-magento-init script tag?
- What is the difference between the text/x-magento-init and the data-mage-init methods of JavaScript module execution?
##### Describe advanced methods of executing JavaScript modules
- How do you execute a JavaScript module in an AJAX response and in dynamic code stored in a string?

#### 2.4 Describe jQuery UI widgets in Magento
[devdocs](https://devdocs.magento.com/guides/v2.3/javascript-dev-guide/widgets/jquery-widgets-about.html),[magently](https://magently.com/blog/magento-2-javascript-jquery-widgets/), [ibnab](https://www.ibnab.com/en/blog/magento-2/magento-2-ui-components-video-use-jquery-widgets-and-requirejs-in-practice), [kiwicommerce](https://kiwicommerce.co.uk/blog/how-to-create-a-jquery-widget-in-magento-2/), [jason](https://jason.codes/2019/06/magento-2-create-jquery-ui-widget/), [rakeshjesadiya](https://www.rakeshjesadiya.com/how-to-create-custom-jquery-widget-using-magento-2/)
##### Describe how Magento uses jQuery widgets, and demonstrate an understanding of the $.mage object
- What is the role of jQuery widgets in Magento?
- What are typical widgets?
- How are Magento jQuery widget modules structured?
##### Describe how Magento executes jQuery widgets
- How are Magento jQuery widgets executed with data-mage-init and text/x-magento-init?

#### 2.5 Demonstrate ability to customize JavaScript modules
[devdocs](https://devdocs.magento.com/guides/v2.3/javascript-dev-guide/javascript/js_mixins.html), [alanstorm](https://alanstorm.com/the-curious-case-of-magento-2-mixins/), [webkul](https://webkul.com/blog/use-js-mixins-magento2/), [meetanshi](https://meetanshi.com/blog/use-javascript-mixins-in-magento-2/), [learnmagento2](https://learnmagento2.wordpress.com/2018/01/09/magento-2-javascript-mixins/)
##### Use Magento JavaScript mixins for customizations
- Describe advantages and limitations of using mixins.
- What are cases where mixins cannot be used?
##### Describe how to customize jQuery widgets in Magento
- How can a new method be added to a jQuery widget?
- How can an existing method of a jQuery widget be overridden?
- What is the difference in approach to customizating jQuery widgets compared to other Magento JavaScript
module types?

## <a name="3">3 Magento Core JavaScript Library 19%</a> [Go to Top](#top)

#### 3.1 Demonstrate understanding of the mage library
[alanstorm](https://alanstorm.com/magento-2-uielement-standard-library-primer/), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/css-topics/theme-ui-lib.html), [magecomp](https://magecomp.com/blog/how-to-use-built-in-jquery-library-in-magento-2/)

##### Describe different types of Magento JavaScript templates
- Magento pseudo ES6 literals and underscore templates in Magento
##### Describe how to use storage and cookies for JavaScript modules
- How do you use cookies in the module?
- How isDemonstrate the ability to use the popup and modal widgets
 localStorage used in Magento?
##### Demonstrate the ability to use the JavaScript translation framework
- How are CSV translations exported to be available in JavaScript modules?
- How is a new translation phrase added using JavaScript methods?
##### Describe the capabilities of the JavaScript framework utils components
- What are the different components available through the mage/utils module?
##### Demonstrate the ability to use and customize the validation module
- What is the architecture of the validation modules in Magento?
- How can a custom validation rule be added?
- How can an existing rule be customized?

#### 3.2 Demonstrate understanding of mage widgets
[devdocs](https://devdocs.magento.com/guides/v2.3/coding-standards/code-standard-jquery-widgets.html), [stackexchange](https://magento.stackexchange.com/questions/276369/magento-2-extend-mage-quicksearch-widget), [alanstorm](https://alanstorm.com/modifying-a-jquery-widget-in-magento-2/)

##### Describe the collapsible jQuery widgets in the Magento JavaScript library and how to use them
- Which collapsible widgets are available in Magento?
- How do you use them?
##### Demonstrate the ability to use the popup and modal widgets
- How do you create a new popup, dialog, or modal with the Magento components?
##### Describe the different jQuery widgets in the Magento JavaScript library
- Which other widgets are available in the Magento JavaScript library?
- How do you use them?
#### 3.3 Demonstrate the ability to use the customer-data module
[devdocs](https://devdocs.magento.com/guides/v2.3/extension-dev-guide/cache/page-caching/private-content.html), [stackexchange](https://magento.stackexchange.com/questions/112948/magento-2-how-do-customer-sections-sections-xml-work), [](https://amasty.com/blog/how-to-use-sections-in-magento-2/), [belvg](https://belvg.com/blog/customer-data-management-in-magento-2.html), [webkul](https://webkul.com/blog/sections-magento-2/), [alanstorm](https://alanstorm.com/understanding-the-limitations-of-sectionsxml/), [magecomp](https://magecomp.com/blog/use-section-xml-file-magento-2/), [hellomagento2](https://www.hellomagento2.com/private-content/)

##### Demonstrate understanding of the customer-data module concept
- What is private data?
- Why do we need to store information in the browser?
- What are performance considerations?
##### Demonstrate understanding of how to use the customer-data module in customizations
- How is the customer-data module structured?
- How is data accessed, invalidated, or set?
##### Describe how to use sections.xml to modify the information available through the customer-data module
- How can a sections.xml file be used to add a new section and to modify the invalidation rules of an existing section?
- How can a customization change the way existing sections work?

## <a name="4">4 UI Components 24% </a>[Go to Top](#top)
#### 4.1 Demonstrate understanding of Knockout customizations
[devdocs](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/concepts/knockout-bindings.html), [amasty](https://amasty.com/blog/tips-and-examples-of-using-knockout-in-magento-2/), [alanstorm](https://alanstorm.com/magento_2_knockoutjs_integration/), [mageplaza](https://www.mageplaza.com/devdocs/how-to-call-children-in-Magento-2-template-knockout.html), [inchoo](https://inchoo.net/magento-2/knockout-js-in-magento-2/), [bizspice](https://www.bizspice.com/blog/post/knockout-js-in-magento-2), [belvg](https://belvg.com/blog/one-more-magento-2-javascript-certified-developer-at-belvg.html)

##### Describe Magento modifications to the Knockout template engine
- Describe the remote template engine, template syntax, custom tags and attributes, and the rendering mechanism
##### Demonstrate the ability to use the custom Knockout bindings provided by Magento
- Where can a full list of custom bindings be found?
- What are they used for?
- What alternatives are there?
##### Describe the Knockout scope binding
- What is the purpose of the scope binding?
- What Knockout problem does it solve?
- How exactly does this binding work?
##### Demonstrate the ability to use the scope binding in customizations
- How is the scope binding used?
- How do nested scopes work?
- How can data of a parent scope be accessed from a child?
- How can the scope binding be applied to HTML in Ajax responses?
#### 4.2 Demonstrate understanding of Magento UI components
[devdocs](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/bk-ui_comps.html), [alanstorm](https://alanstorm.com/magento_2_introducing_ui_components/), [magently](https://magently.com/blog/magento-ui-components-custom-grid/), [devdocs](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/concepts/ui_comp_config_flow_concept.html), [hexascholars](https://www.hexascholars.com/code-snippet/custom-uicomponent-creation-on-the-front-end-in-magento-2/)

##### Describe how uiComponents are executed in Magento
- What is the difference in uiCompnent execution compared to other JavaScript module types?
- What does it mean to "execute a uiComponent"?
- Why do we need the app component to execute uiComponents?
- What is the role of the layout component?
##### Describe the structure of a UiComponent
- What is uiClass?
- How does it instantiate uiComponents?
- How can existing component instances be accessed?
- How can a uiComponent be modified?
- How do you extend an existing uiComponent?
- What is the role of the uiElement and uiCollection modules?
##### Demonstrate the ability to create a uiComponent with its own data, or operate with data of existing uiComponents
- How does a uiComponent access the data it needs?
- What are the requirements for a subcomponent to provide data?
- How can data be loaded by Ajax?
- How can a component receive the data when it is loaded?
##### Describe the process of sharing data between components
- How can one uiComponent instance access data of another instance?
- How can components communicate while taking into account their asynchronous nature?
#### 4.3 Demonstrate the ability to use UI components
[devdocs](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/bk-ui_comps.html), [inviqa](https://inviqa.com/blog/technical-guide-magento-2-checkout), [stackoverflow](https://stackoverflow.blog/2018/01/11/brutal-lifecycle-javascript-frameworks/)

##### Describe the uiComponents lifecycle
- What are the stages of uiComponent execution?
- What is the role of the layout module, and how does it load components, children, and data?
- What are the types of components it supports?
Demonstrate the ability to use uiComponents configuration to modify existing instances and create new instances
- Describe the definitons.xml file and uiComponent instance XML files.
- How can you modify an existing instance of a uiComponent using a configuration file?
- What is the role of the Magento layout in the uiComponent workflow?
#### 4.4 Demonstrate understanding of grids and forms
[mage-world](https://www.mage-world.com/blog/grid-and-form-in-magento-2-admin-panel-part-1.html), [webkul](https://webkul.com/blog/create-ui-form-magento2-part-1/), [magestore](https://www.magestore.com/magento-2-tutorial/how-to-show-listing-items-grid-on-the-form-in-magento-2/), [meetanshi](https://meetanshi.com/blog/create-admin-grid-magento-2/)

##### Customize existing grids and create new grids
- How do you create a grid?
- How do you add an image column, standard validation, custom validation rules, and custom column types to a grid?
- How do you modify existing grids?
- How do you customize the data loading process for a grid, including filters and sorting?
##### Customize existing forms and create new forms
- How do you create a form, a form with tabs, a form with groups of fields, a form with dynamic fields (when one field change will cause a change in another place)?
- How do you customize existing forms?
- How do you add validation to fields, including custom validation rules?
- How can you add a file upload field, an image field, and a custom field to a form?

## <a name="5">5 Checkout 12% </a>[Go to Top](#top)

#### 5.1 Demonstrate understanding of checkout architecture
[inviqa](https://inviqa.com/blog/technical-guide-magento-2-checkout), [devdocs](https://devdocs.magento.com/guides/v2.3/howdoi/checkout/checkout_overview.html), [devdocs](https://devdocs.magento.com/guides/v2.3/howdoi/checkout/checkout_customize.html), [mageplaza](https://www.mageplaza.com/devdocs/custom-checkout-component-magento-2.html), [paulnrogers](https://paulnrogers.com/definitive-guide-magento-2-checkout-best-practice/), [interactiv4](https://www.interactiv4.com/modulos-y-extensiones-en/perder-miedo-al-checkout-i4/?lang=en), [alanstorm](https://alanstorm.com/how-magentos-checkout-application-updates/), [inchoo](https://inchoo.net/magento-2/magento-2-checkout)
##### Describe key classes in checkout JavaScript: Actions, models, and views
- What are actions, models, and views used for in checkout?
- How does Magento store checkout data?
- What type of classes are used for loading/posting data to the server?
- How does a view file update current information?
##### Demonstrate the ability to use the checkout steps for debugging and customization
- How do you add a new checkout step?
- How do you modify the order of steps?
- Debug the data flow of each step.
- How do you customize a step's logic?
##### Customize the shipping step rendering and saving
- How does Magento save information about the shipping address for different types of checkout (logged in with default address, without default address, not logged in)?
- How does Magento obtain the list of available shipping methods?
- Which events can trigger this process?
- How does Magento save a selected address and shipping method?
#### 5.2 Demonstrate understanding of payments
[mageplaza](https://www.mageplaza.com/devdocs/magento-2-create-payment-method/), [devdocs](https://devdocs.magento.com/guides/v2.3/javascript-dev-guide/javascript/js-resources.html), [devdocs](https://devdocs.magento.com/guides/v2.3/architecture/archi_perspectives/present_layer.html), [javatpoint](https://www.javatpoint.com/architecture-of-magento-2)
##### Describe the architecture of JavaScript payment modules
- Add new payment method and payment methods renderers.
- Modify an existing payment method.
##### Demonstrate the ability to use the payment data flow for debugging and customizations
- How does a payment method send its data to the server?
- What is the correct approach to deal with sensitive data?
##### Demonstrate the ability to customize and debug the order placement process in JavaScript
- Describe the data flow during order placement
- Which modules are involved?
- How can the payment step be separated from the order placement?

### Ref
- [devdocsJs](https://devdocs.magento.com/guides/v2.3/javascript-dev-guide/bk-javascript-dev-guide.html)
- []()
- []()
