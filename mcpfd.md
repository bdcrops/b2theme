# Magento 2 Certified Professional Front End Developer Exam

This exam consists primarily of scenario-based questions in a multiple-choice format. Sample questions are included at the end of this guide.
Test time: 90 minutes. Passing score: 63% or above, 60 questions. Available to take remotely or at a test center.

## <a name="top"> Exam topics and the percentage covered in the test.</a>
- [1. Create Themes 7%](#1)
- [2. Magento Design Configuration System 7%](#2)
- [3. Layout XML in Themes 18%](#3)
- [4. Create and Customize Template Files 8%](#4)
- [5. Static Asset Deployment 5%](#5)
- [6. Customize and Create JavaScript 17%](#6)
- [7. Use LESS/CSS to Customize Magento Look and Feel 8%](#7)
- [8. Customize the Look and Feel of Specific Magento Pages 22%](#8)
- [9. Implement Internationalization of Frontend Pages 5%](#9)
- [10. Magento Development Process 3%](#10)

##  Topics and Objectives

### <a name="1">1 Create Themes 7%</a>

#### 1.1 Describe folder structure for local and Composer-based themes</a>
 [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-structure.html), [mageplaza](https://www.mageplaza.com/devdocs/file-structure-magento-2.html), [meetanshi](https://meetanshi.com/blog/create-child-theme-in-magento-2/), [templatetoaster](https://blog.templatetoaster.com/create-magento-theme/), [devdocs1](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-structure.html), [devdocs](https://devdocs.magento.com/guides/v2.3/cloud/howtos/custom-theme.html), [github](https://github.com/MagePsycho/magento2-starter-theme), [meetanshi](https://meetanshi.com/blog/install-a-theme-in-magento-2/), [belvg](https://belvg.com/blog/another-certified-magento-2-professional-front-end-developer.html), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-structure.html)

- In which folders can themes be located?
- What determines where a theme is installed?
- What is the difference if a theme is installed in one or the other of the possible directories?
#### 1.2 Describe the different folders of a theme
[medium](https://medium.com/the-andela-way/understanding-magento-2-folder-structure-704733be3d8b), [belvg](https://belvg.com/blog/directory-structure-and-locating-different-files-in-magento2.html)


- Which folders can exist within a theme?
- Which folders are optional and which are required?
- What is the purpose of each of the folders?
#### 1.3 Describe the different files of a theme
[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-structure.html), [bssthemes](https://bssthemes.com/blog/magento-2-luma-theme-location/), [amasty](https://amasty.com/knowledge-base/magento-2-file-and-folder-structure.html), [cloudways](https://www.cloudways.com/blog/magento-folder-structure/)

- Which files are required to be present in a theme?
- Which files are optional?
- What is the purpose of each of the different file types?

#### 1.4 Understand the usage of Magento areas: adminhtml/base/frontend
[belvg](https://belvg.com/blog/magento-2-areas-adminhtml-base-and-frontend.html), [stackexchange](https://magento.stackexchange.com/questions/96719/module-view-base-folder-in-magento2),[alanstorm](https://alanstorm.com/magento_2_adding_frontend_files_to_your_module/), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-structure.html), [devdocs2](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/debug-theme.html), [mageplaza](https://www.mageplaza.com/devdocs/file-structure-magento-2.html), [dckap](https://www.dckap.com/blog/magento-2-theme-structure/), [belvg](https://belvg.com/blog/utilizing-themes-and-the-template-structure-in-magento-2.htm)

- Which design areas exist?
- What is the difference between them, and what do design areas have in common?
- What are design areas used for?
- How can design areas be utilized for custom themes or customizations?

### <a name="2">2 Magento Design Configuration System 7% </a> [Go to Top](#top)

#### 2.1 Describe the relationship between themes

[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-inherit.html), [belvg](https://belvg.com/blog/themes-in-magento-2-creation-inheritance-and-hierarchy.html), [stackexchange](https://magento.stackexchange.com/questions/92181/magento-2-theme-type-0physical-1virtual-2staging-when-to-use), [icecubedigital](https://www.icecubedigital.com/blog/magento-2-theme-development-customization-step-by-step-guide/), [swissuplabs](https://docs.swissuplabs.com/m2/argento/customization/custom-theme/)

- What type of relationships can exist between themes?
- What is the difference between a parent theme and a child theme?
- How can the relationship between themes be defined and influenced?
- How is that taken into account when creating a custom theme or customizing an existing theme?

#### 2.2 Configure the design system using the options found in the Admin UI under
[magento](https://support.magento.com/hc/en-us/articles/360005032794-Customize-design-configuration-in-Magento-Admin), [devdocs](https://devdocs.magento.com/guides/v2.3/install-gde/install/cli/install-cli-subcommands-store.html), [belvg](https://belvg.com/blog/plus-one-magento-2-professional-front-end-developer.html), [inviqa](https://inviqa.com/blog/magento-2-tutorial-how-use-new-frontend-templating-system)

- Content > Design > Configuration
- How do the configuration settings affect theme rendering? What happens if a theme is added or removed?
- What common mistakes can be made in regard to these settings?

#### 2.3 Apply a temporary theme configuration
[belvg](https://belvg.com/blog/magento-fallback-configuration-default-and-specific-themes-packages-design-exceptions-temporary-theme-configuration.html), [devdocs](https://devdocs.magento.com/guides/v2.3/config-guide/cli/config-cli-subcommands-config-mgmt-set.html), [github](https://github.com/magento-notes/magento2-exam-notes/blob/master/),  [amasty](https://amasty.com/knowledge-base/magento-2-admin-panel-tutorial.html)

-  temporary theme configuration to a store view using the options found in the Admin UI under Content > Design > Schedule?
- What is the purpose of this feature? How does it influence rendering if a design change is scheduled?
- What happens at the end of a scheduled design?
- How is full page caching involved?

#### 2.4 Understand the differences and similarities between Content > Design >
- Content > Design >Configuration and > Schedule to configure the design fallback
- What is the effect if both options are used at the same time?
[docs-ce](https://docs.magento.com/m2/ce/user_guide/design/configuration.html), [docs-ce](https://docs.magento.com/m2/ce/user_guide/design/schedule.html), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-apply.html), [mageplaza](https://www.mageplaza.com/kb/how-to-schedule-change-design-magento-2.html), [mageplaza](https://www.mageplaza.com/kb/configure-design-magento-2.html), [stackexchange](https://magento.stackexchange.com/questions/153234/content-design-config-shows-no-records-on-fresh-2-1-3-install/247231), [belvg](https://belvg.com/blog/configuring-site-design-in-magento-2-admin-panel.html), [belvg2](https://belvg.com/blog/how-to-use-the-magento-design-fallback-system.html), [magestore](https://www.magestore.com/magento-2-tutorial/general-configuration-magento-2/), [stackoverflow](https://stackoverflow.com/questions/45862997/magento-2-1-4-in-admin-panel-content-design-configuration-page-no-data-i)


### <a name="3">3 Layout XML in Themes 18%</a> [Go to Top](#top)

#### 3.1 Demonstrate knowledge of all layout XML directives and their arguments
 [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/layouts/xml-instructions.html), [belvg](https://belvg.com/blog/using-layout-and-xml-schema-in-magento-2.html), [danielnavarroymas](http://www.danielnavarroymas.com/magento-certification-describe-directives-of-magento-layout-xml/), [alanstorm](https://alanstorm.com/magento-2-layout-arguments-vs-action-methods/), [gordonlesti](https://gordonlesti.com/magento-2-email-template-layout-directives/)

- What layout XML elements exist and what is their purpose?
- What is the purpose of the attributes that are available on blocks and other elements?

#### 3.2 Describe page layouts and their inheritance
[belvg](https://belvg.com/blog/magento-2-certification-page-layouts-and-their-inheritance.html), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/layouts/layout-extend.html), [stackexchange](https://magento.stackexchange.com/questions/210851/magento2-what-is-the-difference-between-layout-and-page-layout), [mage2](https://mage2.pro/t/topic/3902), [1](https://mage2.pro/t/topic/752), [stackoverflow](https://stackoverflow.com/questions/55418987/overriding-magento-2-base-empty-page-layout), [mageplaza](https://www.mageplaza.com/devdocs/how-to-create-magento-2-theme.html)

- How can the page layout be specified?
- What is the purpose of page layouts?
- How can a custom page layout be created?
- Where are the existing page layouts used?
- How can the root page layout be specified for all pages and for specific pages?

#### 3.3 Demonstrate understanding of layout handles and corresponding files
[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/layouts/layout-overview.html), [belvg](https://belvg.com/blog/module-layout-handles-in-magento-2.html), [stackexchange](https://magento.stackexchange.com/questions/106134/magento-2-how-to-use-the-layout-handle-customer-logged-in), [rakeshjesadiya](https://www.rakeshjesadiya.com/list-of-layout-xml-for-a-current-page-magento-2/), [knightdale](https://www.knightdale-computer-repair.com/coding/magento-2-targeting-a-specific-cms-page-using-layout-xml/), [emiprotechnologies](https://www.emiprotechnologies.com/technical_notes/magento-technical-notes-60/post/different-product-layout-based-on-product-custom-attribute-in-magento-2-630), [alanstorm](https://alanstorm.com/magento_2_javascript_css_layout_woes/), [meetanshi](https://meetanshi.com/blog/update-layout-using-observer-in-magento-2/), [scommerce](https://www.scommerce-mage.com/blog/create-your-own-page-with-your-own-layout-and-template-files-in-magento.html)

- How can the available layout handles for a given page be determined?
- How do you add a new layout handle?
- What is the purpose of layout handles?
- What are the most commonly used layout handles?
- How can layout handles be used during theme customization?

#### 3.4 Understand the differences between containers and blocks
[belvg](https://belvg.com/blog/understanding-containers-blocks-and-actions-in-magento-2-layout-structure.html), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/layouts/layout-overview.html), [stackexchange](https://magento.stackexchange.com/questions/256478/what-is-the-functional-difference-of-block-container-in-magento-2), [alankent](https://alankent.me/2015/01/24/magento-2-containers-and-blocks/), [awaredigital](https://www.awaredigital.co.uk/blog/remove-blocks-or-containers-from-a-layout-in-magento-2/), [ostraining](https://www.ostraining.com/blog/magento/blocks-widgets/), [webkul](https://webkul.com/blog/remove-blocks-containers-layout-magento2/)

- What is the purpose of blocks? What is the purpose of containers?
- How can containers be used in theming?
- How can blocks be used in theming?
- What is the default block type?
- How can the order of rendered child blocks be influenced both in containers and in blocks?

#### 3.5 Describe layout XML override technique

[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/layouts/layout-override.html), [stackexchange](https://magento.stackexchange.com/questions/140626/how-can-i-override-this-vendor-layout-file-with-my-custom-layout-file-in-magento), [magecomp](https://magecomp.com/blog/override-layout-xml-block-magento-2/), [inchoo](https://inchoo.net/magento-2/override-magento-2-layout-product-page-example/), [classyllama](https://www.classyllama.com/blog/template-override-m2), [belvg](https://belvg.com/blog/overriding-layout-files-in-magento-2.html), [magenticians](https://magenticians.com/magento-2-override-block/), [magenest](https://store.magenest.com/blog/override-magento-2-core-layout/), [mageplaza](https://www.mageplaza.com/devdocs/overriding-native-template-file-magento-2.html)

- How can layout XML be overridden?
- How can layout overriding be used in theming?
- What are consequences of layout overrides during upgrades?
- What is the effect of layout overrides on compatibility?

#### 3.6 Understand layout merging
[belvg](https://belvg.com/blog/magento-2-certification-layout-merging-overview.html), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/layouts/layout-overview.html), [magento](https://magento-quickies.tumblr.com/post/168961542080/layout-xml-merging-in-magento-2), [magentoextensions](https://www.magentoextensions.org/documentation/class_magento_1_1_framework_1_1_view_1_1_model_1_1_layout_1_1_merge.html), [mirasvit](https://mirasvit.com/knowledge-base/how-to-combine-javascript-files-in-magento-2.html), [stackoverflow](https://stackoverflow.com/questions/47894566/magento-2-element-referencecontainer-attribute-after-the-attribute-after)

- What is layout merging?
- How do design areas influence merging?
- How can merging remove elements added earlier?
- What are additive changes and what are overriding changes during layout merging?

#### 3.7 Understand processing order of layout handles and other directives
[stackexchange](https://magento.stackexchange.com/questions/251318/magento-2-understand-processing-order-of-layout-handles-and-other-directives), [ipfs](https://ipfs-sec.stackexchange.cloudflare-ipfs.com/magento/A/question/251318/magento-2-understand-processing-order-of-layout-handles-and-other-directives.html), [belvg](https://belvg.com/blog/magento-2-certification-layout-merging-overview.html), [belvg2](https://belvg.com/blog/using-layout-xml-to-customize-a-magento-theme.html), [alanstorm](https://alanstorm.com/layout-xml-merging-in-magento-2/), [inviqa](https://inviqa.com/blog/magento-2-tutorial-what-is-new-front-end-developers)

- In what order are layout handles processed?
- In what order is layout XML merged within the same handle?
- How can the processing order be influenced?
- What are common problems arising from the merge order of layout declarations?

#### 3.8 Set values on block instances using layout XML arguments
[stackexchange](https://magento.stackexchange.com/questions/112025/magento-2-passing-arguments-in-layout-xml-to-block), [belvg](https://belvg.com/blog/layout-xml-directives-and-their-arguments-in-magento-2.html), [belvg](https://belvg.com/blog/how-to-use-blocks-in-magento-2-development.html), [jamersan](https://jamersan.com/super-guide-theming-magento-2-part-3-3/), [mage2](https://mage2.pro/t/topic/243), [magecomp](https://magecomp.com/blog/create-dynamic-generated-field-system-configuration-magento-2/)

- How can arguments be set on blocks?
- Which data types are available?
- What are common arguments for blocks?

#### 3.9 Customize a theme's appearance with etc/view.xml
[dev](https://dev.to/asrar7787/magento-2-theme-what-is-etc-view-xml-3hki), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-images.html), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-inherit.html), [magestore](https://www.magestore.com/magento-2-tutorial/magento-2-theme-create-sample-custome-theme/), [bizspice](https://www.bizspice.com/blog/post/how-to-build-a-custom-theme-in-magento-2-part-1)

- What is the etc/view.xml file used for?
- How can it be used to customize a theme?
- How can values from etc/view.xml be used during theming?
- How does theme inheritance influence values from etc/view.xml?

### <a name="4"> 4 Create and Customize Template Files 8%</a> [Go to Top](#top)

#### 4.1 Assign a customized template file using layout XML
[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/templates/template-walkthrough.html), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-apply.html), [cloudways](https://www.cloudways.com/blog/magento-2-layouts-blocks-templates/), [qaisarsatti](https://blog.qaisarsatti.com/magento_2/assign-custom-theme-programmatically-to-store-in-magento-2/)

- How can a customized template file be assigned to a block using layout XML?
- How does overriding a template affect upgradability?
- What precautions can be taken to ease future upgrades when customizing templates?

#### 4.2 Override a native template file with a customized template file, using the design fallback
[mageplaza](https://www.mageplaza.com/devdocs/overriding-native-template-file-magento-2.html), [magestore](https://www.magestore.com/magento-2-tutorial/override-template-file-magento-2/)

- How can the design fallback be used to render customized templates?
- How does that influence upgradability?
- How can you determine which template a block renders?

#### 4.3 Describe conventions used in template files
[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/templates/template-override.html), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/conventions.html), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/templates/template-walkthrough.html), [belvg](https://belvg.com/blog/magento-2-directory-module-theme-catalogue-structure.html), [mageants](https://www.mageants.com/blog/how-to-create-custom-theme-in-magento-2.html)

- What conventions are used in PHP templates?
- Why aren’t the common PHP loop and block constructs used?
- Which common methods are available on the $block variable?
- How can a child block be rendered?
- How can all child blocks be rendered?
- How can a group of child blocks be rendered?

#### 4.4 Render values of arguments set via layout XML
[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/layouts/xml-instructions.html), [pixiemedia](https://www.pixiemedia.co.uk/blog/setting-getting-block-variables-in-magento2.html)

- How can values set on a block in layout XML be accessed and rendered in a template?

#### 4.5 Demonstrate ability to escape content rendered and template files

[devdocs](https://devdocs.magento.com/page-builder/docs/reference/configurations.html), [belvg](https://belvg.com/blog/another-certified-magento-2-professional-front-end-developer.html]), [kinsta](https://kinsta.com/blog/eliminate-render-blocking-javascript-css/), [stackexchange](https://magento.stackexchange.com/questions/251399/how-to-render-html-in-x-magento-template), [devdocs](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/components/ui-htmlcontent.html), [devdocs](https://devdocs.magento.com/page-builder/docs/create-custom-content-type/step-2-add-templates.html), [stackoverflow](https://stackoverflow.com/questions/55404227/how-to-render-html-tags-in-admin-product-grid-magento2-3), [codextblog](http://www.codextblog.com/magento-2/how-to-render-an-html-using-an-ajax-call-in-magento-2-module/)

- How can dynamic values be rendered securely in HTML, HTML attributes, JavaScript, and in URLs?

### <a name="5">5 Static Asset Deployment 5%</a> [Go to Top](#top)

#### 5.1 Describe the static asset deployment process for different file types
[devdocs](https://devdocs.magento.com/guides/v2.3/config-guide/cli/config-cli-subcommands-static-view.html), [devdocs2](https://devdocs.magento.com/guides/v2.3/config-guide/cli/config-cli-subcommands-static-deploy-strategies.html), [amasty](https://amasty.com/knowledge-base/magento-2-deploy-static-content.html), [github](https://github.com/magento/magento2/issues/22880), [stackexchange](https://magento.stackexchange.com/questions/255428/admin-url-css-and-js-not-working)

- What commands must be executed to deploy static file types?
- What are common mistakes during the process?

#### 5.2 Describe the effect of deploy modes on frontend development
[devdocs](https://devdocs.magento.com/guides/v2.3/config-guide/bootstrap/magento-modes.html), [amasty](https://amasty.com/knowledge-base/magento-2-modes-set-developer-production-mode.html), [digitalstartup](https://digitalstartup.co.uk/t/translating-magento-2-installing-custom-language-pack-s/242), [dzone](https://dzone.com/articles/5-essential-magento-performance-tips-most-develope), [goivvy](https://www.goivvy.com/blog/speed-up-magento)

- What are the differences between development and production mode in regard to frontend development?

#### 5.3 Demonstrate your understanding of LESS > CSS deployment and its restrictions in development
[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/css-topics/css-preprocess.html), [belvg](https://belvg.com/blog/how-to-deploy-static-files-in-magento-2.html), [magenticians](https://magenticians.com/deploy-magento-2-static-content/), [stackexchange](https://magento.stackexchange.com/questions/291299/static-content-deploy-issue-for-magento-2-3-2), [meetanshi](https://meetanshi.com/blog/magento-2-static-content-deploy/), [weltpixel](https://support.weltpixel.com/hc/en-us/articles/360015798914-How-LESS-CSS-Generation-works-in-Pearl-Theme-Magento-developer-corner-), [astrio](https://astrio.net/blog/magento2-frontend-speedup1/)

- Which LESS compilation options are available in Magento?
- How are they different?
- How do they influence the developer workflow during theming?

### <a name="6">6 Customize and Create JavaScript 17%</a> [Go to Top](#top)

#### 6.1 Include custom JavaScript on pages
[belvg](https://belvg.com/blog/how-to-include-custom-javascript-on-pages-in-magento-2.html), [devdocs](https://devdocs.magento.com/guides/v2.3/javascript-dev-guide/javascript/custom_js.html), [stackexchange](https://magento.stackexchange.com/questions/266477/how-add-custom-js-and-css-to-registration-page-in-magento-2?noredirect=1&lq=1), [choosepizzi](https://www.choosepizzi.net/magento-2-create-a-custom-module-for-add-custom-js-css/), [jamersan](https://jamersan.com/introduction-javascript-magento-2/), [amasty](https://amasty.com/blog/lazyload-images-and-more-swift-magento-2/), [weltpixel](https://support.weltpixel.com/hc/en-us/articles/115000705293-How-to-customize-css-xml-phtml-js-files-in-Magento-2-examples-Tutorial-), [mageplaza](https://www.mageplaza.com/devdocs/javascript-bundling-group-combine-js-files-magento-2.html), [magentodeveloper](https://magentodeveloper.in/add-popup-to-product-view-page-magento2.html), [magecomp](https://magecomp.com/blog/add-new-custom-step-section-checkout-magento-2/), [algolia](https://www.algolia.com/doc/integration/magento-2/guides/create-a-custom-extension/?language=php), [jason](https://jason.codes/2019/06/magento-2-create-jquery-ui-widget/)

- What options exist to include custom JavaScript on a page?
- What are the advantages and disadvantages of inline JavaScript?
- How can JavaScript be loaded asynchronously on a page?
- How can JavaScript on a page be configured using block arguments in layout XML?
- How can it be done directly in a .phtml template?

#### 6.2 Demonstrate understanding of using jQuery
[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/css-topics/css-jquery.html), [devdocs](https://devdocs.magento.com/guides/v2.3/javascript-dev-guide/bk-javascript-dev-guide.html), [stackexchange](https://magento.stackexchange.com/questions/290633/magento-2-using-jquery-on-html-page), [stackoverflow](https://stackoverflow.com/questions/58300471/jquery-is-not-defined-in-magento-2), [webkul](https://webkul.com/blog/how-to-extend-jquery-widget-in-magento-2/), [paulmestereaga](http://paulmestereaga.com/magento-2-extend-jquery-widget/), [jamersan](https://jamersan.com/adding-jquery-slider-magento-2-site/), [magestore](https://www.magestore.com/magento-2-tutorial/how-to-override-magento-js-core-in-magento-2/), [sherocommerce](https://sherocommerce.com/jquery-widgets/), [rakeshjesadiya](https://www.rakeshjesadiya.com/how-to-show-loader-widget-in-ajax-call-magento-2/), [meetanshi](https://meetanshi.com/blog/get-magento-2-url-in-js-file/)

- Demonstrate understanding of jQuery and jQuery UI widgets.
- Demonstrate understanding of how to use Magento core jQuery widgets.
- How can jQuery UI Widget methods be instantiated?
- How can you call jQuery UI Widget methods?
- How can you add new methods to a jQuery UI Widget?
- How can a jQuery UI Widget method be wrapped with custom logic?

#### 6.3 Demonstrate understanding of requireJS
[jamersan](https://jamersan.com/introduction-javascript-magento-2/), [devdocs](https://devdocs.magento.com/guides/v2.3/javascript-dev-guide/javascript/js-resources.html), [devdocs](https://devdocs.magento.com/guides/v2.2/javascript-dev-guide/javascript/requirejs.html), [devdocs](https://devdocs.magento.com/guides/v2.3/javascript-dev-guide/javascript/custom_js.html), [belvg](https://belvg.com/blog/how-to-use-jquery-and-requirejs-in-magento-2-javascript-solutions.html), [stackexchange](https://magento.stackexchange.com/questions/282144/how-to-include-a-third-party-javascript-in-magento-2-using-requirejs), [stackoverflow](https://stackoverflow.com/questions/56131061/requirejs-in-magento-2-gives-me-undefined-instead-of-my-library), [magestore](https://www.magestore.com/magento-2-tutorial/disable-requirejs-cache-magento-2/), [magebay](https://www.magebay.com/docs/how-to-use-requirejs-and-ajax-in-magento-2-extension/), [meetanshi](https://meetanshi.com/blog/add-custom-js-file-in-magento-2-admin-panel/), [magentoway](https://www.magentoway.com/posts/how-to-optimize-magento2-performance-by-advanced-javascript-bundling/), [webnexs](https://www.webnexs.com/blog/kb/disable-requirejs-cache-magento-2/), [toweringmedia](https://toweringmedia.com/blog/javascript-init-scripts-magento2/)

- How do you load a file with require.js?
- How do you define a require.js module?
- How are require.js module dependencies specified?
- How are module aliases configured in requirejs-config.js?
- How do you regenerate the compiled requirejsconfig.js file after changes?
- How do you configure module aliases in requirejs-config.js?
- How do you debug which file a requireJS alias refers to?
- Demonstrate that you understand how to create and configure Magento JavaScript mixins.

#### 6.4 Configure JavaScript merging and minify in the Admin UI
[belvg](https://belvg.com/blog/how-to-configure-javascript-merging-and-minify-in-the-admin-ui-in-magento.html), [devdocs](https://devdocs.magento.com/guides/v2.3/performance-best-practices/advanced-js-bundling.html), [devdocs1](https://devdocs.magento.com/guides/v2.3/cloud/live/sens-data-initial.html), [devdocs2](https://devdocs.magento.com/guides/v2.3/javascript-dev-guide/javascript/js-resources.html), [devdocs3](https://devdocs.magento.com/guides/v2.3/config-guide/cli/config-cli-subcommands-static-view.html), [servebolt](https://servebolt.com/articles/advanced-optimization-of-css-and-javascript-in-magento-2/)

- What options are available to configure JavaScript minification and bundling?
- How does Magento minify JavaScript?
- What is the purpose of JavaScript bundling and minification?

#### 6.5 UI component configuration
[devdocs](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/bk-ui_comps.html), [devdocs](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/concepts/ui_comp_config_flow_concept.html), [devdocs](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/howto/new_component_declaration.html), [magently](https://magently.com/blog/custom-products-grid-additional-functionalities/), [stackexchange](https://magento.stackexchange.com/questions/279987/how-to-add-dynamic-filter-in-magento-2-admin-ui-components), [dmytropoperechnyy](https://dmytropoperechnyy.com/how-to-customize-button-ui-component-in-magento-2/), [mageworx](https://www.mageworx.com/blog/how-to-add-a-field-to-custom-options-in-magento-2/)

- How can you specify configuration options on a UiComponent widget in JSON and in Layout XML?
- What configuration options are available on UiComponents?
- How do you specify the ko template for a UiComponent?
- Demonstrate an understanding of default.tracks

#### 6.6 Understanding knockout framework
[belvg](https://belvg.com/blog/what-is-knockout-js-framework.html), [bizspice](https://www.bizspice.com/blog/post/knockout-js-in-magento-2), [magenest](https://store.magenest.com/blog/write-knockoutjs-magento-2/), [rohanhapani](https://www.rohanhapani.com/how-to-use-knockout-js-in-magento-2/), [magestore](https://www.magestore.com/magento-2-tutorial/how-to-write-a-page-using-magento-2-knockout-js/), [codilar](https://www.codilar.com/blog/knockoutjs-in-magento-2/), [sohel](https://sohel.dev/2019/08/04/how-to-create-knockoutjs-custom-binding-in-magento-2/), [devdocs](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/concepts/knockout-bindings.html), [webnexs](https://www.webnexs.com/blog/kb/write-page-using-knockout-js-magento-2/), [jason](https://jason.codes/2019/07/magento-2-ui-component/), [meetanshi](https://meetanshi.com/blog/call-children-in-magento-2-template-knockout/), [devdocs](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/concepts/magento-bindings.html), [magecomp](https://magecomp.com/blog/add-checkout-custom-form-validation-using-knockout-js-magento-2/)

- How do you use knockout.js bindings?
- How do you bind a ko view model to a section of the DOM with the scope binding?
- How do you render a ko template of a UiComponent?
- Demonstrate an understanding of the different types of knockout observables.
- What common ko bindings are used?
- Demonstrate an understanding of ko virtual elements.

#### 6.7 Understanding dependency between components
[devdocs](https://devdocs.magento.com/guides/v2.3/install-gde/trouble/readiness/tshoot_rc_depend.html), [community](https://community.magento.com/t5/Magento-2-x-Technical-Issues/conflicting-component-dependencies-in-Magento-2-3-0/td-p/118186), [devdocs](https://devdocs.magento.com/guides/v2.3/extension-dev-guide/depend-inj.html), [stackexchange](https://magento.stackexchange.com/questions/267537/magento-2-set-dependency-between-two-dropdown-in-ui-form), [magenest](https://store.magenest.com/blog/create-form-use-ui-commagento-2/)

- Demonstrate an understanding of the links, imports, exports, and listens UiComponent configuration directives.

#### 6.8 Understanding string templates
[devdocs](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/concepts/ui_comp_template_literals.html), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/translations/translate_theory.html), [devdocs2](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/concepts/ui_comp_linking_concept.html), [stackexchange](https://magento.stackexchange.com/questions/285265/parse-php-plain-text-to-html-magento-2), [belvg](https://belvg.com/blog/how-to-use-templates-and-layouts-in-magento-2-layout-overview.html), [hexascholars](https://www.hexascholars.com/code-snippet/custom-uicomponent-creation-on-the-front-end-in-magento-2/), [magenest](https://store.magenest.com/blog/javascript-translation-magento-2/)

- Demonstrate an understanding of ES5 string literal templates like ${$.provider}.
- What does $. Inside of ${ } resolve to?

### <a name="7"> 7 Use LESS/CSS to Customize the Magento Look and Feel 8%</a> [Go to Top](#top)

#### 7.1 Explain core concepts of LESS

[belvg](https://belvg.com/blog/plus-one-magento-2-professional-front-end-developer.html), [belvg2](https://belvg.com/blog/another-certified-magento-2-professional-front-end-developer.html), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-structure.html), [devdocs2](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/templates/template-override.html), [training](https://mage.training/magento-2-front-end-development-part-5), [firebearstudio](https://firebearstudio.com/blog/headless-magento-2-pwa.html)

- Describe features like file import via @import directive, reusable code sections via mixins together with parameters and
the usage of variables.
- Demonstrate your understanding of the special variable @arguments.
- Demonstrate how to use the nesting code formatting, and the understanding of media queries together with nesting.
- Describe how the & (Ampersand) works and its function.
- Describe how calculations are possible as well.

#### 7.2 Explain Magento's implementation of LESS (@ magento_directive)
[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/css-topics/css-preprocess.html), [devdocs2](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/css-topics/css_debug.html), [devdocs3](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/responsive-web-design/rwd_css.html), [devdocs4](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/bk-frontend-dev-guide.html), [belvg](https://belvg.com/blog/what-is-css-in-magento-2.html), [belvg](https://belvg.com/blog/another-certified-magento-2-professional-front-end-developer.html), [weltpixel](https://support.weltpixel.com/hc/en-us/articles/360007925833-How-to-Go-Live-with-Magento-2-in-less-than-30-days-using-the-Pearl-Theme-50-step-guide-tutorial-)

- Demonstrate the process from magento-less files via php preprocessing into real LESS files with extracted @import
directives.
- Where can the intermediate files be found?
- What do you have to remember, when you change a less file?
- Which files will be re-processed on file changes?
- Are the original files copied or symlinked in developer environments?

#### 7.3 Describe the purpose of _ module.less, _ extend.less, _ extends.less
[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/css-guide/css_quick_guide_approach.html), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/css-topics/css-preprocess.html), [devdocs2](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/css-guide/css_quick_guide_mode.html), [magenest](https://store.magenest.com/blog/use-less-extend-styling-magento-2/), [ipfs](http://ipfs-sec.stackexchange.cloudflare-ipfs.com/magento/A/question/116248.html), [weltpixel](https://support.weltpixel.com/hc/en-us/articles/360015798914-How-LESS-CSS-Generation-works-in-Pearl-Theme-Magento-developer-corner-), [amasty](https://amasty.com/knowledge-base/magento-2-css.html), [dsanderson](https://dsanderson.co.uk/magento-2-css-less-compilation/)

- Demonstrate LESS has no fallback capabilities and therefor
- magento created @magento_import directives to enable FE devs to inject or replace parts of existing less structures of modules and themes.

#### 7.4 Show configuration and usage of CSS merging and minification
[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/js-bundling.html), [weltpixel](https://support.weltpixel.com/hc/en-us/articles/360007311554-How-to-minify-merge-bundle-of-HTML-CSS-JS-Magento-Cloud-vs-Magento-Admin), [medium](https://medium.com/@techemizen/increase-efficiency-of-your-magento-2-website-with-this-magento-2-speed-optimization-guide-7a611b33121d), [atwix](https://www.atwix.com/magento-2/how-to-disable-javascript-bundling-for-particular-page-in-magento-2/), [emizentech](https://www.emizentech.com/blog/magento-2-speed-optimization-guide.html), [mageworx](https://www.mageworx.com/blog/magento-2-speed-optimization-research-proves-default-functionality-is-enough/), [toptal](https://www.toptal.com/magento/magento-performance-optimization-guide), [olegnax](https://olegnax.com/magento-2-speed-optimization-guide/), [onilab](https://onilab.com/blog/magento-2-performance-speed-optimization-guide/)

- Demonstrate the primary use case for merging and minifaction.
- Determine how these options can be found in the backend.
- Understand the implications merging has in respect to folder traversal.

#### 7.5 Magento UI library usage
 [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/css-topics/theme-ui-lib.html), [devdocs2](https://devdocs.magento.com/guides/v2.3/architecture/frontend_custom_strategies.html), [devdocs3](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/css-topics/css-overview.html), [belvg](https://belvg.com/blog/what-is-css-in-magento-2.html), [belvg2](https://belvg.com/blog/another-certified-magento-2-professional-front-end-developer.html), [magenest](https://store.magenest.com/blog/use-less-extend-styling-magento-2/), [magently](https://magently.com/blog/custom-products-grid-base-xml/), [algolia](https://www.algolia.com/doc/integration/magento-2/how-it-works/front-end/?language=php), [astrio](https://astrio.net/blog/magento2-frontend-speedup1/), [magenticians](https://magenticians.com/magento-2-override-block/), [emiprotechnologies](https://www.emiprotechnologies.com/technical_notes/magento-technical-notes-60/post/ui-component-using-layout-xml-in-magento-2-664), [magestore](https://www.magestore.com/magento-2-tutorial/create-simple-grid-listing-in-magento-2-admin-with-ui-component/)
- Demonstrate your understanding of magento's UI library, a LESS-based library of mixins and variables for many different standard design elements on websites.
- How can you take advantage of the UI library?
- What do you have to do to enable it in your theme?
- Which file is primarily used for basic setup of variables?
- Where can UI library files be found? How can it be extended?
- How can you change specific parts of the UI library?

### <a name="8">8 Customize the Look and Feel of Specific Magento Pages 22%</a> [Go to Top](#top)

#### 8.1 Utilize generic page elements
[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/layouts/layout-types.html), [devdocs2](https://devdocs.magento.com/page-builder/docs/how-to/how-to-create-container-content-type.html), [devdocs3](https://devdocs.magento.com/page-builder/docs/reference/architecture.html), [stackexchange](https://magento.stackexchange.com/questions/265791/magento2-how-to-show-button-in-admin-for-custom-module-page), [stackexchange](https://magento.stackexchange.com/questions/289624/magento-2-update-handle-in-xml-file), [markshust](https://markshust.com/2019/03/13/magic-pass-through-viewmodels-magento-2/), [belvg](https://belvg.com/blog/another-certified-magento-2-professional-front-end-developer.html), [etatvasoft](https://www.etatvasoft.com/blog/magento-2-override-magento-core-files/), [itnext](https://itnext.io/using-cms-blocks-effectively-in-vue-storefront-8020df888844), [codextblog1](http://www.codextblog.com/magento-2/how-to-render-an-html-using-an-ajax-call-in-magento-2-module/)

- Demonstrate an understanding of customizing generic page elements that can be found on most pages:
   - page header and footer []()
   - quick search []()
   - store view (language) switcher  []()
   - mini cart  []()
   - breadcrumbs []()
   - sidebar menu []()

#### 8.2 Customizing product detail pages
 [magestore](https://www.magestore.com/magento-2-tutorial/magento-2-edit-product-page-template-and-layout-in-seconds/), [atwix](https://www.atwix.com/magento-2/add-custom-layout-handle-to-product-page-magento-2/), [ubertheme](https://www.ubertheme.com/magento2/how-to-add-magento-2-product-tabs/), [webkul](https://webkul.com/blog/add-custom-text-under-price-details-on-product-page-magento-2/), [bizspice](https://www.bizspice.com/blog/post/learn-how-to-add-next-previous-button-on-magento2-product-page), [belvg](https://belvg.com/blog/magento-2-certification-page-layouts-and-their-inheritance.html), [magezon](https://blog.magezon.com/customize-magento-2-product-tabs-single-product-page-builder/), [magesolution](http://themes.magesolution.com/supro/doc/detail_page.php), [magecomp](https://magecomp.com/blog/add-custom-options-product-programmatically-magento-2/), [meetanshi](https://meetanshi.com/blog/add-rename-remove-product-info-tabs-in-magento-2/), [mageplaza](https://www.mageplaza.com/blog/customize-options-magento-2-better-product-options.html), [magenest](https://store.magenest.com/blog/how-to-add-custom-fields-product-edit-pages-magento-2/)

- How can design changes (page layout) be configured on product detail pages?[]()
- How can design changes be configured for specific product types?[]()
- How can you use custom layout updates for specific product pages? []()
- Demonstrate an understanding of how to use the container blocks provided by Magento to display additional information on category pages. []()

#### 8.3 Customizing category pages
[weltpixel](https://support.weltpixel.com/hc/en-us/articles/115004938607-How-to-change-category-layout-in-Magento-2-), [atwix](https://www.atwix.com/magento-2/how-to-add-custom-layout-handle-to-category-in-magento-2/), [weltpixel](https://support.weltpixel.com/hc/en-us/articles/115000875534-How-to-configure-category-page-with-without-sidebar), [metagento](https://www.metagento.com/blog/magento-2-set-custom-page-title-for-category-pages), [belvg](https://belvg.com/blog/magento-2-certification-page-layouts-and-their-inheritance.html)

- How can design changes (page layout) be configured on category pages? [1]()
[magestore](https://www.magestore.com/magento-2-tutorial/magento-2-change-category-page-layout-and-custom-theme/), [weltpixel](https://support.weltpixel.com/hc/en-us/articles/115004938607-How-to-change-category-layout-in-Magento-2-), [fishpig](https://fishpig.co.uk/magento/wordpress-integration/layout-xml/)

- How can the layered navigation be configured? [magestore](https://www.magestore.com/magento-2-tutorial/magento-2-how-to-enable-layered-navigation/), [docs](https://docs.magento.com/m2/ee/user_guide/catalog/navigation-layered-filterable-attributes.html), [mageplaza](https://www.mageplaza.com/blog/custom-product-collection-layered-navigation-magento-2.html), [mageplaza2](https://www.mageplaza.com/blog/custom-layered-navigation-in-magento-2.html), [firebearstudio](https://firebearstudio.com/blog/elastic-layered-navigation-for-magento-2.html), [amasty](https://amasty.com/knowledge-base/configure-magento-1-2-filters-with-layered-navigation.html), [amasty2](https://amasty.com/docs/doku.php?id=magento_2:improved_layered_navigation), [magecomp](https://magecomp.com/blog/expand-default-layered-navigation-category-filters-magento-2/)

- Demonstrate an understanding of configuring design inheritance for category pages.[belvg](https://belvg.com/blog/magento-2-certification-page-layouts-and-their-inheritance.html), [devdocs1](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-inherit.html), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-images.html), [stackexchange](https://magento.stackexchange.com/questions/272160/page-layouts-1-column-2-columns-left-2-columns-right-3-column), [magestore](https://www.magestore.com/magento-2-tutorial/magento-2-change-category-page-layout-and-custom-theme/), [magenest](https://store.magenest.com/blog/create-new-theme-magento-2/)

- How can a CMS block be configured as a category landing page? [stackexchange](https://magento.stackexchange.com/questions/265945/how-to-set-cms-block-to-category-in-magento-2-programmatically), [amasty](https://amasty.com/docs/doku.php?id=magento_2:landing_pages), [belvg](https://belvg.com/blog/how-to-add-new-category-in-magento-2.html), [meetanshi](https://meetanshi.com/blog/call-cms-static-block-in-phtml-file-in-magento-2/), [firebearstudio](https://firebearstudio.com/blog/schedule-block-magento-2-extension-by-sharadice.html), [blogtreat](http://www.blogtreat.com/magento-2-creating-cms-static-block-using-installable-script/), [stackexchange](https://magento.stackexchange.com/questions/252641/terms-and-conditions-from-static-block-magento2)

#### 8.4 Customizing CMS pages
- How can design changes (page layout) be configured on CMS pages? [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/layouts/layout-overview.html), [devdocs2](https://devdocs.magento.com/page-builder/docs/how-to/how-to-use-full-width-layouts.html), [jason](https://jason.codes/2019/03/magento-2-create-new-page-layout/), [magecomp](https://magecomp.com/blog/add-custom-cms-page-layout-magento-2/), [weltpixel](https://support.weltpixel.com/hc/en-us/articles/115005199487-How-to-set-a-Homepage-as-the-default-page-for-my-Magento-store-)

- Demonstrate an understanding of static variables in CMS blocks and pages.  
[belvg](https://belvg.com/blog/custom-variables-and-filters-in-static-blocks-in-magento-2.html), [rakeshjesadiya](https://www.rakeshjesadiya.com/how-to-filter-static-block-content-in-template-file-using-magento-2/), [stackexchange](https://magento.stackexchange.com/questions/274114/get-static-block-content-by-identifier-in-helper-class?rq=1), [bizspice](https://www.bizspice.com/blog/post/how-to-add-a-static-block-on-checkout-on-magento-2-using-knockoutjs), [docs](https://docs.magento.com/m2/ee/user_guide/cms/page-builder-tutorial2-blocks.html), [devdocs](https://devdocs.magento.com/guides/v2.3/mtf/mtf_entities/mtf_block.html), [magecomp](https://magecomp.com/blog/pass-data-cms-block-phtml-file-magento-2/), [webnexs](https://www.webnexs.com/blog/kb/add-variable-magento-2-templates/)

- Demonstrate an understanding of the use of CMS template directives (var, store, block, …).  
[atwix](https://www.atwix.com/magento-2/directives/), [stackexchange](https://magento.stackexchange.com/questions/154352/custom-cms-directives-for-magento-2-1), [jamersan](https://jamersan.com/directives-magento-use/), [stackexchange](https://magento.stackexchange.com/questions/245402/magento-2-variable-with-storeviewcode), [inchoo](https://inchoo.net/magento-2/cache/how-to-save-custom-data-cache-magento-2/), [stackoverflow](https://stackoverflow.com/questions/42601199/magento-2-passing-store-variables-to-block-from-layout-xml-file)

#### 8.5 Customizing widgets
- How is a widget instance created?  [toptal](https://www.toptal.com/magento/custom-widgets-in-magento-2) ,[magestore](https://www.magestore.com/magento-2-tutorial/create-widget-magento-2/), [magenticians](https://magenticians.com/create-widget-in-magento-2/), [hostadvice](https://hostadvice.com/how-to/how-to-create-a-custom-widget-in-magento-2/), [magehit](https://magehit.com/blog/how-to-create-magento-2-widget/)

- Where can widgets be used? [classyllama](https://www.classyllama.com/blog/creating-a-custom-widget-in-magento-2), [meetanshi](https://meetanshi.com/blog/create-new-pages-blocks-widgets-using-magento-2-cms/), [devdocs](https://devdocs.magento.com/page-builder/docs/how-to/how-to-add-storefront-widget.html)

- How can a custom widget target be created? [mageplaza](https://www.mageplaza.com/devdocs/magento-2-create-widget/) , [magenest](https://magenest.com/en/create-widget-magento-2/), [cloudways](https://www.cloudways.com/blog/magento-2-custom-widget/)


- Demonstrate an understanding of configuring a widget instance. [magestore](https://www.magestore.com/magento-2-tutorial/how-to-create-magento-2-widget/), [meetanshi](https://meetanshi.com/blog/create-a-custom-widget-in-magento-2/), [rakeshjesadiya](https://www.rakeshjesadiya.com/magento-2-create-custom-category-widget/), [meganmosehauer](https://meganmosehauer.com/tutorial/magento-custom-widget/), [ubertheme](https://www.ubertheme.com/docs/introducing-magento-2-widgets/), [jason](https://jason.codes/2019/06/magento-2-create-jquery-ui-widget/)



#### 8.6 Customizing CMS blocks  [stackexchange](https://magento.stackexchange.com/questions/250432/override-footer-content-with-custom-cms-blocks), [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/layouts/xml-manage.html), [devdocs](https://devdocs.magento.com/guides/v2.3/ext-best-practices/tutorials/custom-widget.html), [magenticians](https://magenticians.com/magento-cms/)

- How do you create and insert CMS blocks? [meetanshi](https://meetanshi.com/blog/call-cms-static-block-in-phtml-file-in-magento-2/), [ibnab](https://www.ibnab.com/en/blog/magento-2), [tigrensolutions](http://tigrensolutions.blogspot.com/2018/11/how-to-add-custom-validate-field-in.html)


- Demonstrate an understanding of the use of CMS template directives (var,store, block, …). [meetanshi](https://meetanshi.com/blog/call-cms-static-block-in-phtml-file-in-magento-2/), [chapagain](https://blog.chapagain.com.np/magento-2-add-update-cms-static-block-via-install-upgrade-script-programmatically/), [belvg](https://belvg.com/blog/how-to-create-menu-in-magento-2-step-by-step-instruction.html), [amasty](https://amasty.com/blog/customize-contact-us-form-in-magento-2/), [javatpoint](https://www.javatpoint.com/create-and-manage-cms-in-magento-2), [stackexchange](https://magento.stackexchange.com/questions/281222/magento-2-how-to-update-block-programmatically)

#### 8.7 Customizing customer account pages
- How do you remove or add an item from the customer account navigation using layout XML? [stackexchange](https://magento.stackexchange.com/questions/91648/how-to-add-remove-links-on-my-account-navigation-magento2), [zemez](https://zemez.io/magento/support/how-to/magento-2-remove-customer-account-navigation-links/), [aureatelabs](https://aureatelabs.com/how-to/how-to-remove-unnecessary-customer-account-links-in-magento-2/), [inchoo](https://inchoo.net/magento-2/managing-my-account-navigation-links-magento-2/),
[mage2](https://mage2.pro/t/topic/1571)

- Demonstrate an understanding of formatting customer addresses. [magento](https://docs.magento.com/m2/ee/user_guide/stores/attributes-customer-address-templates.html), [mageplaza](https://www.mageplaza.com/kb/how-change-customer-address-template-in-invoices-shipments-credit-memo-pdf-magento-2.html), [bsscommerce](https://bsscommerce.com/blog/Magento-2-change-customer-address-templates-Magento+2/), [mageguides](http://mageguides.com/modify-customer-address-templates-magento-2/), [rakeshjesadiya](https://www.rakeshjesadiya.com/how-to-convert-shipping-address-into-html-format-using-magento-2/), [firebearstudio](https://firebearstudio.com/blog/magento-2-get-default-billing-and-shipping-address-by-customer.html)



#### 8.8 Customizing one-page checkout
- Demonstrate an understanding of the container blocks provided in the Magento checkout to display additional information. [belvg](https://belvg.com/blog/change-one-page-checkout-multi-address-checkout-in-magento.html), [mageplaza](https://www.mageplaza.com/devdocs/magento-2-optimize-default-checkout-page.html) ,[inviqa](https://inviqa.com/blog/magento-2-tutorial-how-use-new-frontend-templating-system) ,[inchoo](https://inchoo.net/magento-2/display-cms-block-magento-2-checkout/)



#### 8.9 Understand customization of transactional email templates

- How do you create and assign custom transactional email templates? [magefan](https://magefan.com/blog/edit-magento2-transactional-email-template), [webkul](https://webkul.com/blog/magento2-create-custom-email-templates/), [magestore](https://www.magestore.com/magento-2-tutorial/how-to-configure-email-templates-in-magento-2/)



- How do you use template variables available in all emails? [mageplaza](https://www.mageplaza.com/kb/how-to-customize-email-template-transactional-email-magento-2.html), [meetanshi](https://meetanshi.com/blog/list-of-default-variables-used-in-magento-2-email-templates/), [nwdthemes](https://nwdthemes.com/2018/05/18/how-to-manage-custom-email-templates-in-magento-2/), [magenticians](https://magenticians.com/customize-email-templates-magento-2/) , [amasty](https://amasty.com/knowledge-base/magento-2-email-templates.html), [stackexchange](https://magento.stackexchange.com/questions/282673/how-to-get-customer-id-customer-firstname-with-customer-account-edited-event)

- How do you access properties of variable objects (for example, var order.getCustomer.getName)? [inchoo](https://inchoo.net/magento-2/cache/how-to-save-custom-data-cache-magento-2/),
[stackexchange](https://magento.stackexchange.com/questions/282673/how-to-get-customer-id-customer-firstname-with-customer-account-edited-event) [chapagain](http://blog.chapagain.com.np/magento-2-get-order-info-order-item-payment-info-billing-address-shipping-address-by-order-id-increment-id/)


- How can you create a link to custom images from transactional email templates? [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/templates/template-email.html) ,
- How do you create links to store pages in transactional email templates? [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/templates/template-email.html) , [amasty](https://amasty.com/blog/create-edit-magento-2-email-templates/) ,[belvg](https://belvg.com/blog/customize-magento-2-email-template-settings.html), [themes](https://themes.email/magento/a-massive-guide-to-customizing-magento-emails.html), [firebearstudio](https://firebearstudio.com/blog/responsive-transactional-emails-for-magento-2-by-magetrend.html), [magestore](https://www.magestore.com/magento-2-tutorial/magento-2-introduction-about-email-templates/)



### <a name="9"> 9 Implement Internationalization of Frontend Pages 5%</a> [Go to Top](#top)

#### 9.1 Create and change translations
- Demonstrate an understanding of internationalization (i18n) in Magento. [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/translations/translate_practice.html),[commerce](https://developers.front-commerce.com/docs/magento2/i18n.html),[nwdthemes](https://nwdthemes.com/2019/03/05/magento-2-language-package-explained/)

- What is the role of the theme translation dictionary, language packs, and database translations? [appjetty](https://devdocs.magento.com/guides/v2.3/config-guide/cli/config-cli-subcommands-i18n.html), [appjetty](https://www.appjetty.com/blog/multi-language-store-magento2)


- Understand the pros and cons of applying translations via the translate.csv file versus the core_translate table.[devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/translations/xlate.html)

- In what priority are translations applied?  [webinterpret](https://www.webinterpret.com/au/blog/ecommerce-translation-magento/), [atwix](https://www.atwix.com/magento/manage-translation-system/), [belvg](https://belvg.com/blog/how-to-internationalize-a-magento-store.html),[stackexchange](https://magento.stackexchange.com/questions/170997/magento-2-priority-of-translation-proper-way)


#### 9.2 Translate theme strings

- Translate theme strings for .phtml, emails, UI components, .js files? [belvg](https://belvg.com/blog/plus-one-magento-2-professional-front-end-developer.html), [magestore](https://www.magestore.com/magento-2-tutorial/how-to-translate-a-string-by-code-in-magento-2/)

- Demonstrate an understanding of string translation in JavaScript? [devdocs](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/translations/translate_theory.html),[firebearstudio](https://firebearstudio.com/blog/how-to-make-javascript-strings-translatable-localizable-in-magento-2.html),[mrvts](https://mrvts.wordpress.com/2018/07/19/magento-2-javascript-translation-sometime-translate-sometime-not-work-why-and-how-to-fix/),[webnexs](https://www.webnexs.com/blog/kb/convert-string-by-code-magento-2/),[integer](https://www.integer-net.com/magento-2-translations-contribution/)


###  <a name="10"> 10 Magento Development Process 3%</a> [Go to Top](#top)

#### 10.1 Determine ability to manage cache
- Determine ability to manage cache? [devdocs](https://devdocs.magento.com/guides/v2.3/config-guide/cli/config-cli-subcommands-cache.html)
- Demonstrate an understanding of configuring the Magento cache types for development and production. [mageworx](https://www.mageworx.com/wiki/magento2-cache)



#### 10.2 Understand Magento console commands
- How do you switch between deploy modes? [devdocs](https://devdocs.magento.com/guides/v2.3/config-guide/cli/config-cli-subcommands-mode.html), [belvg](https://belvg.com/blog/how-to-switch-between-deploy-modes-in-magento-2.html)


- What bin/magento commands are commonly run during frontend development? [devdocs](https://devdocs.magento.com/guides/v2.3/config-guide/cli/config-cli-subcommands.html),[mageplaza](https://www.mageplaza.com/devdocs/magento-2-command-line-interface-cli.html),[emiprotechnologies](https://www.emiprotechnologies.com/technical_notes/magento-technical-notes-60/post/magento-2-useful-commands-list-391)




***
### Ref:

- [DevdocsFdSeries](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/bk-frontend-dev-guide.html)
- [devdocsJsSeries](https://devdocs.magento.com/guides/v2.3/javascript-dev-guide/bk-javascript-dev-guide.html)
- [devdocsUiSeries](https://devdocs.magento.com/guides/v2.3/ui_comp_guide/bk-ui_comps.html)

- [jamersan Series3](https://jamersan.com/lets-get-started-theming-magento-2-part-1/)


***

#### Magento 2 Certified Professional Front End Developer Exam
Example Questions See the Answer Key following the questions for answers.

##### Question 1: You are developing a German language theme for the Magento Marketplace named mytheme. In your Magento installation you have a third-party German language package installed. The theme “mytheme” already contains a mytheme/i18n/de_DE.csv file. The graphic designer wants you to rename the Add to Cart button to make the text shorter. Keeping upgradability in mind, where do you add the new string?

- A. Override the Magento_Catalog/view/frontend/templates/product/view/addtocart.phtml template in
mytheme and replace the string.
- B. Add the string to mytheme/i18n/de_DE.csv
- C. Add the string to the third-party German language package.
- D. Add the translation to the core_translate database table.
Reference: Magento Dev Docs: Use translation dictionary to customize strings
https://devdocs.magento.com/guides/v2.2/frontend-dev-guide/translations/theme_dictionary.html

##### Question 2: Which three properties are set in theme.xml?
- A. Title of a theme
- B. Composer package version
- C. Theme area: frontend or adminhtml
- D. Theme preview image
- E. Parent theme
Reference: Magento Dev Docs: Create a new storefront theme
http://devdocs.magento.com/guides/v2.2/frontend-dev-guide/themes/theme-create.html

##### Question 3: You need to add a custom block of HTML to the header of every page using a layout file in MyCompany/mytheme. Keeping upgradability in mind, how do you add the block?

- A. Put your customization in MyCompany/mytheme/layout/extend.xml
- B. Include <extend file="Magento_Theme::default.xml"> in your MyCompany/mytheme/Magento_Theme/layout/default.xml
- C. Put your customization in MyCompany/mytheme/Magento_Theme/layout/default.xml
- D. Keep track of your changes and apply them to Magento/Theme/layout/default.xml after upgrade

Reference: Magento Dev Docs: Extend a layout
http://devdocs.magento.com/guides/v2.2/frontend-dev-guide/layouts/layout-extend.html

##### Question 4: A merchant asks you to add frontend validation to their newsletter form. You notice the form has the following attributes: <form class="form newsletter” novalidate id="newsletter-validate-detail"> Which of the following choices will add frontend validation?

- A. Add form_key input inside of form.
- B. Remove the novalidate attribute from form.
- C. Add a validation object using data-mage-init attribute.
- D. Add the class mage-validate to form.

Reference: Magento Dev Docs: Calling and initializing JavaScript
https://devdocs.magento.com/guides/v2.2/javascript-dev-guide/javascript/js_init.html

#### Answer Key
- Question 1 Answer: B
- Question 2 Answers: A, D, E
- Question 3 Answer: C
- Question 4 Answer: C
