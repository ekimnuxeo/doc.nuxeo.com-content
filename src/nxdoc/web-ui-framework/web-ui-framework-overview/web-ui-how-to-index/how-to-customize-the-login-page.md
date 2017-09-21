---
title: How to Customize the Login Page
review:
    comment: ''
    date: ''
    status: ok
details:
    howto:
        excerpt: Learn how to customize the login page using an XML extension.
        level: Beginner
        tool: Code editor
        topics: 'JSF, Theme'
labels:
    - howto
    - last-review-20141106
    - theme
    - login-page
confluence:
    ajs-parent-page-id: '22380880'
    ajs-parent-page-title: Web UI How-To Index
    ajs-space-key: NXDOC60
    ajs-space-name: Nuxeo Platform Developer Documentation — 6.0
    canonical: How+to+Customize+the+Login+Page
    canonical_source: 'https://doc.nuxeo.com/display/NXDOC60/How+to+Customize+the+Login+Page'
    page_id: '22380675'
    shortlink: g4BVAQ
    shortlink_source: 'https://doc.nuxeo.com/x/g4BVAQ'
    source_link: /display/NXDOC60/How+to+Customize+the+Login+Page
history:
    - 
        author: Manon Lumeau
        date: '2016-02-09 15:34'
        message: ''
        version: '38'
    - 
        author: Solen Guitter
        date: '2014-11-06 12:02'
        message: ''
        version: '37'
    - 
        author: Solen Guitter
        date: '2014-11-06 12:01'
        message: add link to the explorer
        version: '36'
    - 
        author: Solen Guitter
        date: '2014-11-06 11:42'
        message: ''
        version: '35'
    - 
        author: Gildas Lefevre
        date: '2014-11-05 15:24'
        message: >-
            NXDOC-363: Split the page in two, a beginner page and an advanced
            one
        version: '34'
    - 
        author: Gildas Lefevre
        date: '2014-11-05 12:18'
        message: 'NXDOC-363: Update How-tos'
        version: '33'
    - 
        author: Anahide Tchertchian
        date: '2014-11-04 16:18'
        message: ''
        version: '32'
    - 
        author: Solen Guitter
        date: '2014-10-03 15:39'
        message: ''
        version: '31'
    - 
        author: Manon Lumeau
        date: '2014-09-17 12:13'
        message: ''
        version: '30'
    - 
        author: Manon Lumeau
        date: '2014-09-16 17:43'
        message: ''
        version: '29'
    - 
        author: Manon Lumeau
        date: '2014-09-16 17:41'
        message: ''
        version: '28'
    - 
        author: Solen Guitter
        date: '2014-01-23 12:03'
        message: ''
        version: '27'
    - 
        author: Solen Guitter
        date: '2014-01-23 11:59'
        message: ''
        version: '26'
    - 
        author: Anahide Tchertchian
        date: '2013-12-04 16:12'
        message: ''
        version: '25'
    - 
        author: Anahide Tchertchian
        date: '2011-07-13 17:24'
        message: ''
        version: '24'
    - 
        author: Anahide Tchertchian
        date: '2011-07-13 17:23'
        message: ''
        version: '23'
    - 
        author: Stéfane Fermigier
        date: '2010-12-04 11:36'
        message: ''
        version: '22'
    - 
        author: Stéfane Fermigier
        date: '2010-12-04 11:32'
        message: ''
        version: '21'
    - 
        author: Florent Guillaume
        date: '2010-08-18 16:50'
        message: ''
        version: '20'
    - 
        author: Florent Guillaume
        date: '2010-07-27 17:08'
        message: ''
        version: '19'
    - 
        author: Stéfane Fermigier
        date: '2010-07-22 16:58'
        message: ''
        version: '18'
    - 
        author: Stéfane Fermigier
        date: '2010-07-22 14:43'
        message: ''
        version: '17'
    - 
        author: Stéfane Fermigier
        date: '2010-07-22 10:28'
        message: ''
        version: '16'
    - 
        author: Stéfane Fermigier
        date: '2010-07-22 10:24'
        message: ''
        version: '15'
    - 
        author: Stéfane Fermigier
        date: '2010-07-22 10:16'
        message: ''
        version: '14'
    - 
        author: Stéfane Fermigier
        date: '2010-07-22 09:15'
        message: ''
        version: '13'
    - 
        author: Stéfane Fermigier
        date: '2010-07-22 09:10'
        message: ''
        version: '12'
    - 
        author: Stéfane Fermigier
        date: '2010-07-22 08:55'
        message: ''
        version: '11'
    - 
        author: Stéfane Fermigier
        date: '2010-07-22 08:51'
        message: ''
        version: '10'
    - 
        author: Stéfane Fermigier
        date: '2010-07-21 20:11'
        message: ''
        version: '9'
    - 
        author: Stéfane Fermigier
        date: '2010-07-21 20:06'
        message: ''
        version: '8'
    - 
        author: Stéfane Fermigier
        date: '2010-07-21 19:21'
        message: ''
        version: '7'
    - 
        author: Stéfane Fermigier
        date: '2010-07-21 19:02'
        message: ''
        version: '6'
    - 
        author: Stéfane Fermigier
        date: '2010-07-21 18:39'
        message: ''
        version: '5'
    - 
        author: Stéfane Fermigier
        date: '2010-07-21 18:24'
        message: ''
        version: '4'
    - 
        author: Stéfane Fermigier
        date: '2010-07-21 18:18'
        message: ''
        version: '3'
    - 
        author: Stéfane Fermigier
        date: '2010-07-21 18:12'
        message: ''
        version: '2'
    - 
        author: Stéfane Fermigier
        date: '2010-07-21 18:01'
        message: ''
        version: '1'

---
The basic customization can be made by extending the service `org.nuxeo.ecm.platform.ui.web.auth.service.PluggableAuthenticationService` for the point [`loginScreen`](http://explorer.nuxeo.org/nuxeo/site/distribution/Nuxeo%20Platform-6.0/viewExtensionPoint/org.nuxeo.ecm.platform.ui.web.auth.service.PluggableAuthenticationService--loginScreen).

This point allows you to configure the Login Screen : header, footer, styles, openid providers ... The variable `${org.nuxeo.ecm.contextPath}` can be used to avoid hardcoding the default application path (/nuxeo).

Let's create the component `org.nuxeo.sample.loginPage`.

{{#> panel type='code' heading='src/main/resources/OSGI-INF/login-contribution.xml'}}

```xml
<component name="org.nuxeo.sample.loginPage">
  <extension target="org.nuxeo.ecm.platform.ui.web.auth.service.PluggableAuthenticationService" point="loginScreen">
    <loginScreenConfig>
      <bodyBackgroundStyle>url("${org.nuxeo.ecm.contextPath}/img/newBackground.jpg") 0px 0px no-repeat #000</bodyBackgroundStyle>
      <disableBackgroundSizeCover>false</disableBackgroundSizeCover>
      <headerStyle></headerStyle>
      <footerStyle></footerStyle>
      <loginBoxBackgroundStyle>url("${org.nuxeo.ecm.contextPath}/img/newLoginBox.jpg") 0 0 no-repeat #ff0000</loginBoxBackgroundStyle>
      <loginBoxWidth>400px</loginBoxWidth>
      <logoUrl>${org.nuxeo.ecm.contextPath}/img/newLogo.png</logoUrl>
      <logoAlt>MyCompany</logoAlt>
      <logoWidth>113</logoWidth>
      <logoHeight>20</logoHeight>
    </loginScreenConfig>
  </extension>
</component>
```

{{/panel}}<div class="row" data-equalizer data-equalize-on="medium"><div class="column medium-6">{{#> panel heading='Related How-Tos'}}

*   [How to Declare the CSS and Javascript Resources Used in Your Templates]({{page page='how-to-declare-the-css-and-javascript-resources-used-in-your-templates'}})
*   [undefined]()
*   [undefined]()
*   [How to Add a New Style to Default Pages]({{page page='how-to-add-a-new-style-to-default-pages'}})
*   [How-To Index]({{page page='how-to-index'}})

{{/panel}}</div><div class="column medium-6">{{#> panel heading='Related Documentation'}}

*   [Theme in Developer Documentation]({{page page='theme'}})
*   [Branding in Studio Documentation]({{page space='studio' page='branding'}})
*   [Runtime and Component Model]({{page page='runtime-and-component-model'}})
*   [Web UI Framework]({{page page='web-ui-framework'}})
*   [Online UI Style Guide](http://showcase.nuxeo.com/nuxeo/styleGuide/)

{{/panel}}</div></div>