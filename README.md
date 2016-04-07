# nakedsass - an unopinionated SASS Framework (v2)

	naked
	/'neIkId/
	adjective
	1. (of a person or part of the body) without clothes
	2. (especially of feelings, behaviour or css) expressed openly; undisguised; without addition or embellishment.


## Our Mandate

* unopinionated
* manage the fundamemtals (normalisation, specificity, inheritance & the cascade)
* be intuitive, useful and reusable
* include base styles layouts/patterns/components and tools

In order to meet these, we need to make this thing be two things - naked and easy.

## Structure

	/src
		/base
		/components
		/tools
		/vendor
	/styles
	_config.scss
	main.scss
	old-ie.scss


## Changes

* ADDED   New Structure - Framework moved to Src, _config and styles brought to root
* UPDATED Library now Src and split into base , components (l-), tools (mixins etc) & vendor
* UPDATED _mq_custom & _variables to _config
* REMOVED _setup.scss - the main.scss files handles inclusions of partials well enough
* REMOVED Library/_Defaults.scss - the main.scss files handles inclusions of partials well enough
* UPDATED main.scss to reflect updates
* UPDATED SASS MQ to latest version n.b. uses $until instead of $to (because? marginalia)
