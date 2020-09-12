
Language Support for HTL (HTML Template Language) by Adobe Experience Manager (AEM)
=====================


Quick Start
============
1. Install the Extension
2. Write some amazing HTL code in .html file.
3. Test sly auto-complete features

Features
=========
* Code completion
* Code outline
* Code folding
* Code snippets
    * HTL
    * Fields and dialogs (coming soon...)
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.Checkbox.html
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.ColorInput.html
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.ColumnView.html
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.Icon.html
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.Multifield.html
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.NumberInput.html
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.Search.html
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.Radio.html
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.Select.html
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.SelectList.html
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.Textfield.html
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.Slider.html
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.Tooltip.html
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.StepList.html  2
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.Switch.html 
    * https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/Coral.Textarea.html

    * ==> https://helpx.adobe.com/experience-manager/6-5/sites/developing/using/reference-materials/coral-ui/coralui3/components.html




See the [changelog](CHANGELOG.md) for the latest release.


Code Snippets
==========================
The following settings are supported:

* `component` : Creates a component.
* `template` : Creates a component markup and references a template.
* `sly` : Creates a sly tag with a data-sly attribute.
* `sly.resource` : Creates a sly element with a data-sly-resource attribute.
* `sly.test` : Creates a sly element with a data-sly-test attribute.
* `sly.test.var` : Creates a sly element with an identified data-sly-test attribute.
* `sly.list` : Creates a sly element with a data-sly-repeat and a dynamic tag element (It's recommended to use data-sly-repeat instead of list)
* `sly.repeat` : Creates a sly element with a data-sly-repeat and a dynamic tag element.
* `sly.clientlib` : Creates a sly element with a data-sly-use clientlib definition.
* `sly.call` : Creates a sly element with a data-sly-call attribute.
* `sly.call.param` : Creates a sly element with a data-sly-call attribute and a parameter.
* `sly.include` : Creates a sly element with a data-sly-include attribute.
* `data-sly-include` : Creates a data sly include attribute.
* `data-sly-call` : Creates a data sly call attribute.
* `data-sly-element` : Creates a data sly element attribute.
* `data-sly-attribute` : Creates a data-sly-attribute attribute.
* `data-sly-attribute-map` : Creates a data-sly-attribute-map attribute.
* `data-sly-use` : Creates a data sly use attribute.
* `data-sly-use.var` : Creates a data sly use attribute with var name.
* `data-sly-use.var.param` : Creates a sly data use with a var name and one parameter.
* `sly.i18n` : Creates an I18n call.
* `sly.i18n.hint` : Creates an I18n call with a hint.
* `sly.i18n.locale` : Creates an I18n call with a locale attribute.
* `sly.i18n.source` : Creates an I18n call with a source attribute.
* `sly.i18n.2param` : Creates an I18n call with two dynamic parameters.
* `sly.i18n.1param` : Creates an I18n call with one dynamic parameter.
* `sly.i18n.full` : Creates an I18n full tag.
* `sly.join` : Creates a sly join.
* `sly.context` : Creates a sly context.
* `sly.inStr` : Creates an 'in' relational string operator.
* `sly.inArray` : Creates an 'in' relational array operator.

Feedback
===============
* File a bug in [GitHub Issues](https://github.com/olmanslm/htl-for-vscode/issues).
* [Tweet us](https://twitter.com/olmanslm/) with other feedback.


License
===============
MIT, See [LICENSE](https://opensource.org/licenses/MIT) for more information.