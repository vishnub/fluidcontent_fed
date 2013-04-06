TYPO3 extension Fluid Content FED: Fluid Content Elements using FED
===================================================================

## What is it?

A collection of general purpose Fluid Content Elements written for `EXT:fluidcontent` using ViewHelpers from `EXT:fed`.

## What does it do?

Provides the template files and TypoScript setup necessary to use the included elements.

## How does it do it?

By leveraging the integration logic provided by `EXT:fluidcontent` - enabling use of specially constructed Fluid templates as
content elements, much like the Flexible Content Elements concept from TemplaVoila.

## How is it installed?

Download, install the extension and include the static TypoScript configuration.

## How is it used?

After installation and inclusion of the static TypoScript, the included content elements will be available as new content element
types when inserting new content.

When inserted, each content element contains a special panel with configuration specifying how to render the content element.

## References

* https://github.com/FluidTYPO3/fluidcontent is a dependency - it is the integration necessary to render Fluid Content Elements
* https://github.com/FluidTYPO3/fed is dependency providing many ViewHelpers used in the Fluid Content Element templates
* https://github.com/FluidTYPO3/fluidcontent_bootstrap is another provider of Fluid Content Elements - written with VHS ViewHelpers
