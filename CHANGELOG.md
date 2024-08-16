## [1.4.18](https://github.com/astahmer/openapi-zod-client/compare/v1.4.17...v1.4.18) (2024-08-16)


### Bug Fixes

* **#116:** rogue semicolon after `discriminatedUnion` ([b1d2af4](https://github.com/astahmer/openapi-zod-client/commit/b1d2af40296d6ea8e0addd5e946c21d847908d01)), closes [#116](https://github.com/astahmer/openapi-zod-client/issues/116)
* **#153:** only convert hyphenated path parameters ([2486ce5](https://github.com/astahmer/openapi-zod-client/commit/2486ce5535f4366a534e027ee1e92293be3034c7)), closes [#153](https://github.com/astahmer/openapi-zod-client/issues/153)
* **#178:** handle $ref in response object ([d897485](https://github.com/astahmer/openapi-zod-client/commit/d897485021271734c54925da53e829689ae06838)), closes [#178](https://github.com/astahmer/openapi-zod-client/issues/178)
* **#67:** treat `null` with higher priority ([9f633cc](https://github.com/astahmer/openapi-zod-client/commit/9f633ccc7ae9da74970ec57f68df3e138eca6f39)), closes [#67](https://github.com/astahmer/openapi-zod-client/issues/67)
* **#73:** fallback response to void when no schemas ([1267233](https://github.com/astahmer/openapi-zod-client/commit/126723319262c882d0ee0cd10397472a58dd61de)), closes [#73](https://github.com/astahmer/openapi-zod-client/issues/73)
* added changeset ([5965c3f](https://github.com/astahmer/openapi-zod-client/commit/5965c3fb2ad543de14c4c1546aadb0dc76948a1f))
* adds `react-resizable-panels` library to handle split planes ([4f4e3c7](https://github.com/astahmer/openapi-zod-client/commit/4f4e3c746e13da31b6006068794f1c33b86e2797))
* allow disabling withAlias ([8fdb58f](https://github.com/astahmer/openapi-zod-client/commit/8fdb58f7a301610ba1d0ed5c63a35663e411b7fa))
* bug with exportAllNamedSchemas where schemas will reuse wrong name ([04dd1b5](https://github.com/astahmer/openapi-zod-client/commit/04dd1b549118c8b8e5a3b86f6dbed741f44770c8))
* Bump axios to avoid CVE-2023-45857 ([6e5a589](https://github.com/astahmer/openapi-zod-client/commit/6e5a589025b070308dbc9dd4402d2fa1fac9d349))
* Cannot read properties of undefined (reading 'ref') [#157](https://github.com/astahmer/openapi-zod-client/issues/157) ([4826f3b](https://github.com/astahmer/openapi-zod-client/commit/4826f3b5b370f2cade8b9a00f3e976d68ef4cdf6))
* convert additionalPropsDefaultValue to bool ([fd5f850](https://github.com/astahmer/openapi-zod-client/commit/fd5f850492bf384586d079350f021475014e1767))
* correct createContextWithHook's reference ([9148f79](https://github.com/astahmer/openapi-zod-client/commit/9148f798389259e63452e14dbd7f1562a4d67e66))
* correctly parse required only schema in allOf like https://editor.swagger.io/ ([00ed1ee](https://github.com/astahmer/openapi-zod-client/commit/00ed1ee84ddf88a68e05927395e56a9861394e60))
* default values for "object" type ([b3e273a](https://github.com/astahmer/openapi-zod-client/commit/b3e273abc89a3b7240119ba61ee48ad0de86c38f))
* discriminatedUnion allOf issue ([8dfb265](https://github.com/astahmer/openapi-zod-client/commit/8dfb265ee23bb79b2c8fe0dd979103c89f0bcf4f))
* enum with a single member should not generate a zod union ([6ca10ff](https://github.com/astahmer/openapi-zod-client/commit/6ca10ffae57332ef94e2e3b5f3bacf03a7759bbc))
* explicit undefined check to not exclude falsy default values ([8b710ff](https://github.com/astahmer/openapi-zod-client/commit/8b710ff4cc37a957fcc8769aebdd76162e3f39b7))
* fix tag-file order ([44a5587](https://github.com/astahmer/openapi-zod-client/commit/44a558767e85871b8116038fed3df60c46baf6d1))
* format in array ([74efcf9](https://github.com/astahmer/openapi-zod-client/commit/74efcf95d5173974c56725b0ea60c750d1a14e45))
* generate alias only when asked ([699d828](https://github.com/astahmer/openapi-zod-client/commit/699d82800a8b5f8c6ee35da82ee013847fe81650))
* handle `exclusiveMinimum: false` ([45d5b9b](https://github.com/astahmer/openapi-zod-client/commit/45d5b9b64e54c4cd208df00d8f66382dd67b1f10))
* handle invalid number+enum case if schema.type is Array ([07e5133](https://github.com/astahmer/openapi-zod-client/commit/07e5133e76a286bfa418624dd93de6e7cd864583))
* handle patterns with forward slashes ([303d858](https://github.com/astahmer/openapi-zod-client/commit/303d858b78b8f561d7bf5a2f6458a6646a83f71d))
* invalid dependency when using chaining with tag group strategy ([197316b](https://github.com/astahmer/openapi-zod-client/commit/197316b50b0b84cea977984ae82441f2ce108ea0))
* issue number typo & patch ([1acfb58](https://github.com/astahmer/openapi-zod-client/commit/1acfb58e0230b3ba524087a7954a0fd94fc68a25))
* multiline description ([7224486](https://github.com/astahmer/openapi-zod-client/commit/7224486d79dbaef688a9e7a6bf37df9173eb7d8a))
* pass options when shouldExportAllSchemas is true ([4f27e4a](https://github.com/astahmer/openapi-zod-client/commit/4f27e4a44b65b58386dd2838530d5e718a0c2892))
* pass options when shouldExportAllSchemas is true ([efebdf2](https://github.com/astahmer/openapi-zod-client/commit/efebdf2627e79d2fb759096667d445cc137446fd))
* Pull example schema down locally ([5285acb](https://github.com/astahmer/openapi-zod-client/commit/5285acb1510928cf0ca3434b6d8db431e178d254))
* recursive discriminated union ([42bc083](https://github.com/astahmer/openapi-zod-client/commit/42bc083e7a7e3db2b8d5d0bbd9cfab40a658b162))
* request-body-ref test name typo ([f635e2f](https://github.com/astahmer/openapi-zod-client/commit/f635e2fde38d33d05647e2ccf8de379890ac5fab))
* solves linting errors ([c95b235](https://github.com/astahmer/openapi-zod-client/commit/c95b2350ec2f02c441ff755abedc6302f667d702))
* treat single value string enums as literals ([e89ba55](https://github.com/astahmer/openapi-zod-client/commit/e89ba55ae81143415567cef364b77b1646d25901))
* Update `pnpm-lock.yaml` ([086c019](https://github.com/astahmer/openapi-zod-client/commit/086c01930c1510a7f240dc265cbb97c647420d5e))
* Update output corresponding to spec change ([9c29000](https://github.com/astahmer/openapi-zod-client/commit/9c29000b8d64f45148bf7134de7d148e317b23c7))
* Use existing OpenAPI spec rather than my own ([506c26d](https://github.com/astahmer/openapi-zod-client/commit/506c26d7eab1d3b65a2782efd9dfbdf978ad0447))
* use optional property rather than change existing property ([989320e](https://github.com/astahmer/openapi-zod-client/commit/989320eccd90e9f777832c531fc03340f8b3e7a9))
* use union instead when we can't use discriminatedUnion ([bdde577](https://github.com/astahmer/openapi-zod-client/commit/bdde5777d6587ef2bd407c01d0ec0284118e5699))
* wrap properties beginning with a number in quotes ([95a8e85](https://github.com/astahmer/openapi-zod-client/commit/95a8e853d04f1027bca1851e2fa6ea78f6c8a9e0))


### Features

* **#60:** support schema.type list from openapi 3.1 ([519de14](https://github.com/astahmer/openapi-zod-client/commit/519de1409be4dbe6efb2c25db58669b3c48f38b7)), closes [#60](https://github.com/astahmer/openapi-zod-client/issues/60)
* **#76:** support common PathItemObject["parameters"] ([e88a7cc](https://github.com/astahmer/openapi-zod-client/commit/e88a7ccd35871b09030e822bf11d84f5c419b2f8)), closes [#76](https://github.com/astahmer/openapi-zod-client/issues/76)
* add changeset ([ed50076](https://github.com/astahmer/openapi-zod-client/commit/ed500762c6998fb2976e8ad43a88a3a09d928f2c))
* add changeset ([3ec4915](https://github.com/astahmer/openapi-zod-client/commit/3ec491572e56fc40e3b49cefb58cb6f08600190f))
* add changeset ([f3ee25e](https://github.com/astahmer/openapi-zod-client/commit/f3ee25efc191d0be97231498924fe50fd977fb88))
* add datetime to string fix minmax on num ([3e2406d](https://github.com/astahmer/openapi-zod-client/commit/3e2406d8432e3f1de6edcf635e9946304533e38d))
* add endpointDefinitionRefiner to TemplateContext options ([739ba20](https://github.com/astahmer/openapi-zod-client/commit/739ba209fc8d699cc904a4f382006cf84db18480))
* add exportAllNamedSchemas option to allow exporting duplicate schemas with different names. ([f62be48](https://github.com/astahmer/openapi-zod-client/commit/f62be48c9d66fb432b5b68570f8de4755644d1d5))
* Add JSDoc comments to generated types with `--with-docs` CLI option ([1d398b4](https://github.com/astahmer/openapi-zod-client/commit/1d398b4235be6c6cc17e27f9f733ba0f1799b696))
* add jsdoc tests ([323a34e](https://github.com/astahmer/openapi-zod-client/commit/323a34e08fc33627e6eac8804454a9d665f4f8dc))
* add options.withDescription + cli arg ([290944c](https://github.com/astahmer/openapi-zod-client/commit/290944c4ffd4a2dd80add4dff0a606210b295065))
* add support for oneOf discriminators ([8fb5766](https://github.com/astahmer/openapi-zod-client/commit/8fb5766fabe84b14e7e50ee706131db8abb2b759))
* add withAllResponses option ([096d8b4](https://github.com/astahmer/openapi-zod-client/commit/096d8b4f6bbf0c829ef5dd3c02a11468ba2654b4))
* added requestBody.$ref support ([20e9593](https://github.com/astahmer/openapi-zod-client/commit/20e959358b8b270465e9648b26d5ceaeb33f1c78))
* added test for request body ref ([35bef4b](https://github.com/astahmer/openapi-zod-client/commit/35bef4b885b458e285f0d4682f04e2380d918195))
* allow setting a custom alias generation function ([4b88f29](https://github.com/astahmer/openapi-zod-client/commit/4b88f29b28b86a3b759bb0fe488ebb4633bd58ed))
* config option to control presence of default values in output ([dc16074](https://github.com/astahmer/openapi-zod-client/commit/dc16074f377492d1337ae55366ce54573865adc9))
* **default template:** createApiClient options? ([1b1cde2](https://github.com/astahmer/openapi-zod-client/commit/1b1cde2c7b61ede4494ae829706e5682a05eb85d))
* defaults to withAlias ([a20153b](https://github.com/astahmer/openapi-zod-client/commit/a20153bd66f1f631c6aac5224a418a9e2f8b04c7))
* export createApiClient fn in default templates ([6a111d1](https://github.com/astahmer/openapi-zod-client/commit/6a111d1e1574450e53e6fe91299863223108688c))
* export schemas object in default templates ([85828be](https://github.com/astahmer/openapi-zod-client/commit/85828be2b4ad4f07cb3c969cac94c45a912cc85e))
* **playground:** add api.doc.json default tab ([75edaf1](https://github.com/astahmer/openapi-zod-client/commit/75edaf1d81af0f7b1e4101c2864af44a31f157dd))
* **playground:** update url on input change ([3014ffe](https://github.com/astahmer/openapi-zod-client/commit/3014ffe38c64446ad615352b165da0a4c475bf89))
* reduce dependency count threshold for a type to be imported from common file to just 1 ([e23b42d](https://github.com/astahmer/openapi-zod-client/commit/e23b42de097f2fcf4b83de57a43495779946e449))
* schema refiner ([e812354](https://github.com/astahmer/openapi-zod-client/commit/e812354e578af2dde19b96b2f169e928be129b90))
* support undefined schema refs ([d7a028c](https://github.com/astahmer/openapi-zod-client/commit/d7a028c85e4a942d2a4cf7e1ec93f46572a8efdd))



## [1.4.17](https://github.com/astahmer/openapi-zod-client/compare/v1.4.16...v1.4.17) (2023-01-09)



## [1.4.16](https://github.com/astahmer/openapi-zod-client/compare/v1.4.15...v1.4.16) (2023-01-05)


### Bug Fixes

* **#61:** Combination of enum and minLength leads to invalid zod schmemas ([0c12414](https://github.com/astahmer/openapi-zod-client/commit/0c12414f22e0d7b254bd97f0157a30b5395c240a)), closes [#61](https://github.com/astahmer/openapi-zod-client/issues/61)



## [1.4.15](https://github.com/astahmer/openapi-zod-client/compare/v1.4.14...v1.4.15) (2022-12-13)


### Bug Fixes

* missing zod chains on z.object(..) refs props ([9b5c2cb](https://github.com/astahmer/openapi-zod-client/commit/9b5c2cb1a5ac276538c003a34174a0a5b3618c58))



## [1.4.14](https://github.com/astahmer/openapi-zod-client/compare/v1.4.13...v1.4.14) (2022-12-13)


### Bug Fixes

* schema.type = number with string default should be inlined as number ([b2786b9](https://github.com/astahmer/openapi-zod-client/commit/b2786b9a2a20137e7699822281fddffc01bb2772))



## [1.4.13](https://github.com/astahmer/openapi-zod-client/compare/v1.4.12...v1.4.13) (2022-12-12)


### Bug Fixes

* autofix wrong schema.type case as QoL improvement ([e589663](https://github.com/astahmer/openapi-zod-client/commit/e5896630a9480ad5031d2bd2e451ad4850e9e682))



## [1.4.12](https://github.com/astahmer/openapi-zod-client/compare/v1.4.11...v1.4.12) (2022-12-12)


### Bug Fixes

* **#49:** escape control characters ([5b061cf](https://github.com/astahmer/openapi-zod-client/commit/5b061cfe16c2446bd7bade5cf8356cf6acdd2985)), closes [#49](https://github.com/astahmer/openapi-zod-client/issues/49)



## [1.4.11](https://github.com/astahmer/openapi-zod-client/compare/v1.4.10...v1.4.11) (2022-12-12)


### Bug Fixes

* ParameterObject with missing schema AND content ([20e075c](https://github.com/astahmer/openapi-zod-client/commit/20e075cecf8b10fbab096165de177151b17364bd))



## [1.4.10](https://github.com/astahmer/openapi-zod-client/compare/v1.4.8...v1.4.10) (2022-12-12)


### Bug Fixes

* ParameterObject with content (and no schema) ([a7533a5](https://github.com/astahmer/openapi-zod-client/commit/a7533a51949c4ddb20b7d297583801ade743b58a))



## [1.4.8](https://github.com/astahmer/openapi-zod-client/compare/v1.4.7...v1.4.8) (2022-12-11)


### Bug Fixes

* rm sheep & re-publish since it broke the package.. ([794721a](https://github.com/astahmer/openapi-zod-client/commit/794721aa3a92af695aea4964e5ecbb883ddb9140))



## [1.4.7](https://github.com/astahmer/openapi-zod-client/compare/v1.4.6...v1.4.7) (2022-12-11)


### Bug Fixes

* **#49:** min+max shouldnt mean EXACT but between ([d394d86](https://github.com/astahmer/openapi-zod-client/commit/d394d86059484b32c39bd91aa1897d2373c3d373)), closes [#49](https://github.com/astahmer/openapi-zod-client/issues/49)
* **#49:** missing .and for allOf ([fb2fc0c](https://github.com/astahmer/openapi-zod-client/commit/fb2fc0ce838414d652db4c7fc3e812339dd3a685)), closes [#49](https://github.com/astahmer/openapi-zod-client/issues/49)



## [1.4.6](https://github.com/astahmer/openapi-zod-client/compare/v1.4.5...v1.4.6) (2022-12-10)


### Bug Fixes

* **#49:** numerical enum shouldnt be wrapped in quotes + dont append .int() for them ([cc1ced0](https://github.com/astahmer/openapi-zod-client/commit/cc1ced0e587863d4adc742fcf74e59b6081d3673)), closes [#49](https://github.com/astahmer/openapi-zod-client/issues/49)



## [1.4.5](https://github.com/astahmer/openapi-zod-client/compare/v1.4.0...v1.4.5) (2022-12-07)


### Bug Fixes

* **#45:** add guard on possibly undefined value ([be431b6](https://github.com/astahmer/openapi-zod-client/commit/be431b6f45527a051a3cefaddb9be111fb762c7c)), closes [#45](https://github.com/astahmer/openapi-zod-client/issues/45)
* getZodVarName when result is a ref with chains ([17a7091](https://github.com/astahmer/openapi-zod-client/commit/17a7091842220091a11d3586cec92299a5d5fbcd))
* schema.pattern when not wrapped with /xxx/ ([bda6ecb](https://github.com/astahmer/openapi-zod-client/commit/bda6ecb0a03145d7641c0e41c8aee982461401bc))


### Features

* allow passing own instance of handlebars to generateZodClientFromOpenAPI ([3675691](https://github.com/astahmer/openapi-zod-client/commit/3675691cc7f3f5ac70299f6be1b60c8b7ba88598))



# [1.4.0](https://github.com/astahmer/openapi-zod-client/compare/v1.0.0...v1.4.0) (2022-11-17)


### Bug Fixes

* add updateOutput action where needed ([e9b376f](https://github.com/astahmer/openapi-zod-client/commit/e9b376fd416c7918e8ebd6c1fbd82e66f9ecae1a))
* build ([2d201bf](https://github.com/astahmer/openapi-zod-client/commit/2d201bf1d2e6f622b09282411cb9e3015e6ffd43))
* build + preview + dev (still gets hydration mismatch) ([1659ecb](https://github.com/astahmer/openapi-zod-client/commit/1659ecbc6d407a99f7e3f3171329ae3352656124))
* check for url length before history.replace/copy to clipboard ([dccff7b](https://github.com/astahmer/openapi-zod-client/commit/dccff7be18cce79d2dd7c5f5b15eebb07e41feb2))
* ci ([c2b0ece](https://github.com/astahmer/openapi-zod-client/commit/c2b0ecec82ac1c5c30cc3af35b66504c9c524f54))
* ci ? ([4d4e720](https://github.com/astahmer/openapi-zod-client/commit/4d4e72036ccdad97f9f7cec34193bef3abceb498))
* ci ?? ([0fd0a03](https://github.com/astahmer/openapi-zod-client/commit/0fd0a03c9fea4b3ec616d09513b9db88f746ea8f))
* circular refs detection ([d48fad2](https://github.com/astahmer/openapi-zod-client/commit/d48fad2cb80f0330f8f3d40cd6068498b6968bdb))
* examples ([9501d4b](https://github.com/astahmer/openapi-zod-client/commit/9501d4b90d40667f5bea395d96743e71b9e323d0))
* handle refs with dots in name ([7a1a69d](https://github.com/astahmer/openapi-zod-client/commit/7a1a69df8f077271537ad8c7e3b157b158e7907f))
* is it fine now please ([b119d70](https://github.com/astahmer/openapi-zod-client/commit/b119d7051cd46f8ffaf3e36cb0d5e1cfa675bfc9))
* lib deps ([fee2ce3](https://github.com/astahmer/openapi-zod-client/commit/fee2ce39e6b67c0b85a2a3e7118ce4b3535b0800))
* **lib:** group xxx-file should ignore options.apiClientName ([65b4c43](https://github.com/astahmer/openapi-zod-client/commit/65b4c432b2e17ef0021104d0ab05e0a9e3ff3078))
* **lib:** normalize schema names in template context ([d5705dd](https://github.com/astahmer/openapi-zod-client/commit/d5705ddf681c7a9e7962a73d323bcaa7361a59c8))
* lock ([5fa9865](https://github.com/astahmer/openapi-zod-client/commit/5fa9865123b6ea044014b358519e6d675097f788))
* missing graphs dependencies ([465e06f](https://github.com/astahmer/openapi-zod-client/commit/465e06f10c526cf6aadb8f2780adeac21a1329f1))
* monorepo build ([68d7190](https://github.com/astahmer/openapi-zod-client/commit/68d7190d180606688d1f281f001227ff7326d692))
* mv preconstruct scripts to root ([6f42e65](https://github.com/astahmer/openapi-zod-client/commit/6f42e6545021918f9bd2e418fb8d5880d806a979))
* output TabsList x-axis overflow scroll ([987ff76](https://github.com/astahmer/openapi-zod-client/commit/987ff76412681a7edd63a19cdbcd12f01e515b30))
* **playground:** catch & log errors & notify user ([3fd1186](https://github.com/astahmer/openapi-zod-client/commit/3fd1186815bfe3289b66ba8ff8aa9093638dfac4))
* **playground:** display parsing error ([560d155](https://github.com/astahmer/openapi-zod-client/commit/560d15548abd540c7a151f0cea75c62bc9201b85))
* **playground:** reset groupStrategy to none for schemas-only preset template ([4aca386](https://github.com/astahmer/openapi-zod-client/commit/4aca3867e524af20835f50408efd9251bae9120b))
* pnpx add postinstall in root package ([a11a574](https://github.com/astahmer/openapi-zod-client/commit/a11a57432dc9dd8966b4624b9bcb0982a610dbac))
* pnpx by removing src in files ? ([64c74a7](https://github.com/astahmer/openapi-zod-client/commit/64c74a7ab709e22963547f11970c4779e74c4fd0))
* pnpx maybe ([2e3b004](https://github.com/astahmer/openapi-zod-client/commit/2e3b0044a5a211dee00a8015258efc270f217c27))
* pnpx with postinstall ([2360ef9](https://github.com/astahmer/openapi-zod-client/commit/2360ef91020ef9ae53300402d489d566ac2acb12))
* preconstruct / babel ? ([e0ccf2b](https://github.com/astahmer/openapi-zod-client/commit/e0ccf2bf0b6bb58fd5a39d56c2b3adb976d6056d))
* presetTemplate checked ([8f622bd](https://github.com/astahmer/openapi-zod-client/commit/8f622bd64b98cd746a2923cdb7d80afe3a874f5c))
* server-side package with ssr external + rakkas preview ([a48ea7e](https://github.com/astahmer/openapi-zod-client/commit/a48ea7e8578d09ed25e1421a9bf5140bad04fb5a))
* simplify output templateString ([71a6810](https://github.com/astahmer/openapi-zod-client/commit/71a681082a8c10304695a2e5892fcd2db52953ff))
* update selected template/doc on input when it was empty or when removing file tab ([c851903](https://github.com/astahmer/openapi-zod-client/commit/c851903cb0789af8a0966627556b266cacf10454))
* use fs-extra version that support esm.. ([76a6025](https://github.com/astahmer/openapi-zod-client/commit/76a60253b471d8c7872c7927c3484920029facda))
* using exports ? ([eddfcfe](https://github.com/astahmer/openapi-zod-client/commit/eddfcfe03f46b23b718f48733a6fffb0e4d49396))


### Features

* Actions menu wip + initial template file tab ([270d7ab](https://github.com/astahmer/openapi-zod-client/commit/270d7ab5678a167dd01296009ef3d224772c325f))
* **cli:** add --api-client-name option ([deca178](https://github.com/astahmer/openapi-zod-client/commit/deca1781e988be5e05af71fd8b21b7822efc96c0))
* export getHandlesbars / maybePretty ([ca734db](https://github.com/astahmer/openapi-zod-client/commit/ca734db6e29b72886b98935cd39112969fae3c11))
* FileForm.content as monaco editor ([bdeff23](https://github.com/astahmer/openapi-zod-client/commit/bdeff23f424d6c4df9605ceec6248fe3a005a0f2))
* init docusaurus + vanilla-extract + monaco ([f7e09a5](https://github.com/astahmer/openapi-zod-client/commit/f7e09a5140f49650bce5e8032a54042d29763a2d))
* input files list + editable + reset to petstore btn ([1549de4](https://github.com/astahmer/openapi-zod-client/commit/1549de4f4ffa84fa1b1bf3a16a286af79b3ddb9f))
* **lib:** options.willSuppressWarnings ([5ae86e5](https://github.com/astahmer/openapi-zod-client/commit/5ae86e5fa80b62a755df64e5151af02303049f26))
* **lib:** whence.functions = true ([ab1041f](https://github.com/astahmer/openapi-zod-client/commit/ab1041f044d78222ed89791bdb79e5358d8540bc))
* options builder + preview cli options/ts usage with copy button ([78aed6a](https://github.com/astahmer/openapi-zod-client/commit/78aed6a7903d9b62aeead2112adf7d8cbeabf1f5))
* **playground:** add zod + @zodios/core declarations to monaco ([5e53982](https://github.com/astahmer/openapi-zod-client/commit/5e53982272dbbb3fece0bd68f312917f262cf62c))
* **playground:** customizable prettier config + multiple prettier tabs ([bf68177](https://github.com/astahmer/openapi-zod-client/commit/bf681773fd2c188564f0b3fb4911b6936684ebaa))
* **playground:** go to file ([e28e409](https://github.com/astahmer/openapi-zod-client/commit/e28e40964b3efc504151a305f02754a22a6b2928))
* **playground:** PoC for in-browser lib usage ([772e301](https://github.com/astahmer/openapi-zod-client/commit/772e3013e7d09dd86933cbe3723500f0fd6ce799))
* **playground:** prettier schema in editor ([331e0a8](https://github.com/astahmer/openapi-zod-client/commit/331e0a801e8d296314dc426c0b49c6e89559eee7))
* **playground:** support groupStrategy xxx-file ([26263f7](https://github.com/astahmer/openapi-zod-client/commit/26263f78cd3db62ba5923c67a588f80a28e99ddb))
* save current state to URL & copy to clipboard ([b85b1a6](https://github.com/astahmer/openapi-zod-client/commit/b85b1a647bf1885df32dca516e31257749985380))
* selectedOpenApiFileName/selectedTemplateName ([c44b400](https://github.com/astahmer/openapi-zod-client/commit/c44b4008445e2fa4c907883cd114ee25491f490f))
* **SplitPane:** options + fix overflow auto on 2nd pane ([69b1b2b](https://github.com/astahmer/openapi-zod-client/commit/69b1b2b86dd66eb1ca495a0edd03390a6b89f016))
* updateSelectedTemplateName with override options ([9276cb4](https://github.com/astahmer/openapi-zod-client/commit/9276cb425e7885410146f9c12d42195e8a58b7d6))
* useState/Memo -> Playground.machine ([ab0b863](https://github.com/astahmer/openapi-zod-client/commit/ab0b8632ecd724e32272c059266f81188b98e671))



# [1.0.0](https://github.com/astahmer/openapi-zod-client/compare/v0.9.0...v1.0.0) (2022-10-26)


### Bug Fixes

* add full zod chains for parameters ([b4e5af1](https://github.com/astahmer/openapi-zod-client/commit/b4e5af17c67e3a4d4a04f96dec6145cd4ee3e7cb))
* response acceptance condition should not take default ([2b15d15](https://github.com/astahmer/openapi-zod-client/commit/2b15d151d960fce8aa00d6f5ca71fd09611259cf))


### Features

* adds z.default(xxx) ([1e791f2](https://github.com/astahmer/openapi-zod-client/commit/1e791f22e53c09960e2b89ea06163b469f7098f1))
* **CLI:** add --default-status option ([181ac76](https://github.com/astahmer/openapi-zod-client/commit/181ac765e73739a933842e6191ca43db7e9f1a04))
* options.defaultStatusBehavior ([3c3456f](https://github.com/astahmer/openapi-zod-client/commit/3c3456fe7cbaf9df40a57983a8ae74a6f8935239))
* requestFormat binary, form-url, form-data, text ([099d9da](https://github.com/astahmer/openapi-zod-client/commit/099d9da53e9030324b11c3ebda32765f905e2332))



# [0.9.0](https://github.com/astahmer/openapi-zod-client/compare/v0.8.0...v0.9.0) (2022-10-25)


### Features

* options.complexityThreshold ([dd361cc](https://github.com/astahmer/openapi-zod-client/commit/dd361cc65f333fe75d6c8dbd1f6557e648723eec))
* same schema different name will be re-used ([ed3e320](https://github.com/astahmer/openapi-zod-client/commit/ed3e320f525f40ff7e1e7e9f5171e096ed145db5))


### Reverts

* openapi3-ts to 3.0.2 ([3ab62f9](https://github.com/astahmer/openapi-zod-client/commit/3ab62f95f3b6032ec021dddb53c6417f6f953aec))



# [0.8.0](https://github.com/astahmer/openapi-zod-client/compare/v0.7.0...v0.8.0) (2022-10-24)


### Features

* `options.apiClientName` + custom for groups ([846ae52](https://github.com/astahmer/openapi-zod-client/commit/846ae52c90c24c6eb52809d67f1eea12b1fbc571))
* basic --group-strategy option implementation ([596e9d4](https://github.com/astahmer/openapi-zod-client/commit/596e9d4ed22f6d2893854b9417b5334b7f413cd9))
* **group-strategy:** `xxx-file` common.ts + index.ts ([a0c3170](https://github.com/astahmer/openapi-zod-client/commit/a0c31704488dc421da7cef972852b2a763bcd750))
* include transitive dependencies / sort schemas by deps order + getRefName ([682b0e3](https://github.com/astahmer/openapi-zod-client/commit/682b0e3dd19021f2f0810bdc62d01785b949883e))



# [0.7.0](https://github.com/astahmer/openapi-zod-client/compare/v0.6.1...v0.7.0) (2022-10-21)



## [0.6.1](https://github.com/astahmer/openapi-zod-client/compare/v0.6.0...v0.6.1) (2022-10-20)



# [0.6.0](https://github.com/astahmer/openapi-zod-client/compare/v0.5.0...v0.6.0) (2022-10-20)


### Bug Fixes

* #/xxx/ref params ([8b4417c](https://github.com/astahmer/openapi-zod-client/commit/8b4417c2c21639c6fd69433e1d1dc0ab3aa5eafd))
* ref name with special characters ([4cfb627](https://github.com/astahmer/openapi-zod-client/commit/4cfb62748d848df9bd6612c8912fb9909e1338bd))
* schema.pattern ([f3ef7ae](https://github.com/astahmer/openapi-zod-client/commit/f3ef7aee77fb51516449365140f438f635901d4f))



# [0.5.0](https://github.com/astahmer/openapi-zod-client/compare/ca918dd95164b88277feb2e1c829da54f18f4fc9...v0.5.0) (2022-10-19)


### Bug Fixes

* **#15:** handle missing operationId for requestBody var name ([2d85f42](https://github.com/astahmer/openapi-zod-client/commit/2d85f42ad5e7aabd4b0b8f886493053c932c3f32)), closes [#15](https://github.com/astahmer/openapi-zod-client/issues/15)
* **#21:** infer missing schema as `z.void()` when no matching MediaTypeObject or no ContentObject ([4aa9180](https://github.com/astahmer/openapi-zod-client/commit/4aa9180dde23785680e258bd7d3b3f7da160403b)), closes [#21](https://github.com/astahmer/openapi-zod-client/issues/21)
* $ref in another file ([dcef06a](https://github.com/astahmer/openapi-zod-client/commit/dcef06ad74b462ece0f70d96dc4359e86b2cc4e9))
* add fallback to requestBody.content ([dc0895e](https://github.com/astahmer/openapi-zod-client/commit/dc0895e3adfc4708b3578fca0317d5fb87cfd5b2))
* add missing default response ([704d28f](https://github.com/astahmer/openapi-zod-client/commit/704d28f2f69a3c574f234d0e8b4f029e4d4ff414))
* also generate types for deep dependencies of circular ref types ([cc616ea](https://github.com/astahmer/openapi-zod-client/commit/cc616ea82a4cd169f6473a6fa77b24f02faa377e))
* autofix unusual ref format ([3521840](https://github.com/astahmer/openapi-zod-client/commit/3521840c4db27029a8583c0c363d9e9254dbe754))
* **cli:** append .client after .yaml ([88b86b0](https://github.com/astahmer/openapi-zod-client/commit/88b86b05570d5cdbaba48ce7d387befc444dde8a))
* **cli:** v0.0.7 generateZodClientFromOpenAPI templatePath ([d23069e](https://github.com/astahmer/openapi-zod-client/commit/d23069e505f5799c1aa09fcc5f4a6cedd31f5d9d))
* default schemas overriding 200 response ([c746ef5](https://github.com/astahmer/openapi-zod-client/commit/c746ef5566f5bf49ed8d1ae647b8a445aa6fc15c))
* do not fail if schema doesn't exist ([e7aa1ad](https://github.com/astahmer/openapi-zod-client/commit/e7aa1adb44f35756cd3ba2a61d8f01e224948e51))
* **getZodClientTemplateContext:** replacer / variables order by dependencies ([ca918dd](https://github.com/astahmer/openapi-zod-client/commit/ca918dd95164b88277feb2e1c829da54f18f4fc9))
* handle refs without var name (such as arrays) ([3a613e7](https://github.com/astahmer/openapi-zod-client/commit/3a613e7962cacbcc611ea6231d740aff2e99eae3))
* **issue#2:** format path param ([1896dfb](https://github.com/astahmer/openapi-zod-client/commit/1896dfba6c111efe485c8bd7bb9d6accbcd09b61)), closes [issue#2](https://github.com/issue/issues/2)
* kebab-case-in-props name should be normalized ([0127722](https://github.com/astahmer/openapi-zod-client/commit/0127722000950c8004536d36729ba0dd0767fdc6))
* makeRefHash add letter as prefix ([b1ca8cb](https://github.com/astahmer/openapi-zod-client/commit/b1ca8cb7eb3a0286021fc2278cfba77ec0e09e4f))
* missing maybeReplaceTokenOrVarnameWithRef on errors schema ([2c08ba0](https://github.com/astahmer/openapi-zod-client/commit/2c08ba0cc727ea8a93d5f54d1172608762eb0c09))
* openApiToTypescript openapi integer -> bigint ([943f864](https://github.com/astahmer/openapi-zod-client/commit/943f8648246edc1d729fe7fb00d54419c229d7f8))
* openApiToTypescript with enum as root ([098a8ad](https://github.com/astahmer/openapi-zod-client/commit/098a8ad60a12214c486cc9f0924001ac3cd545cb))
* outputs all deep dependencies as TS for each circular schema ([868107f](https://github.com/astahmer/openapi-zod-client/commit/868107f0c8784613d100fdf3830530fc977a5f13))
* reduce unions to single type when oneOf/anyOf/allOf length is 1 ([d042afb](https://github.com/astahmer/openapi-zod-client/commit/d042afb0027613cbd49dc9be7f717b46c675bdb2))
* reverse order of schema kind in getOpenApiDependencyGraph ([091d469](https://github.com/astahmer/openapi-zod-client/commit/091d46958e240ae8ed39ff5383fc13b7e4986cf1))
* rm bigint -> number ([b0c2181](https://github.com/astahmer/openapi-zod-client/commit/b0c2181455b45dbc7f100cc37efdb813c48133e9))
* rm options.baseUrl default value ([4654ab4](https://github.com/astahmer/openapi-zod-client/commit/4654ab487438047a6659ece7945e523c1878900b))
* rm unnecessary .optional() ([7c46eac](https://github.com/astahmer/openapi-zod-client/commit/7c46eacaa297f85f8374a34fd3ccffbaa9a47e8f))
* unintentional shared context -> make a new object ([5e80cee](https://github.com/astahmer/openapi-zod-client/commit/5e80cee0543f3d863aac655cc25c18f70ac91217))
* use `asApi` helper rather than `as const` ([59ee30b](https://github.com/astahmer/openapi-zod-client/commit/59ee30b101f23d3de5a2ab568525414823d1ca0d))
* var names starting with number ([74c72db](https://github.com/astahmer/openapi-zod-client/commit/74c72db3b7fb6f055854c3aa2c70928d7ab75b33))
* visit additionalProperties to determine schema deps ([15e3f5f](https://github.com/astahmer/openapi-zod-client/commit/15e3f5fc98f0061f153c883799526bc04a9ad9f8))


### Features

* --with-deprecated option (defaults to false) ([9a20e6f](https://github.com/astahmer/openapi-zod-client/commit/9a20e6fe47ca1dfb92646135a9a31d5bccc29660))
* **#13:** implement zodios errors ([216cca1](https://github.com/astahmer/openapi-zod-client/commit/216cca19b07fba2407c94e0a80da0cb8340c3403)), closes [#13](https://github.com/astahmer/openapi-zod-client/issues/13) [#12](https://github.com/astahmer/openapi-zod-client/issues/12)
* **#19:** --export-schemas option ([ed8d7bd](https://github.com/astahmer/openapi-zod-client/commit/ed8d7bd4bdd6357dcada8debcd44178b8f91af4c)), closes [#19](https://github.com/astahmer/openapi-zod-client/issues/19)
* **#23:** withImplicitRequiredProps option ([31adcc2](https://github.com/astahmer/openapi-zod-client/commit/31adcc2053539a8c936291e4b4c7906d7161c1a1)), closes [#23](https://github.com/astahmer/openapi-zod-client/issues/23)
* **#24:** add path params ([82094e9](https://github.com/astahmer/openapi-zod-client/commit/82094e9d0bd73f332d4e5cecffc852c4eaad99b4)), closes [#24](https://github.com/astahmer/openapi-zod-client/issues/24)
* **cli:** -b, -a, -h, -v options ([bc6c249](https://github.com/astahmer/openapi-zod-client/commit/bc6c2495e579a98cda9056ccb9e2e2297435778a))
* **cli:** add template/prettier args ([a8e8ba7](https://github.com/astahmer/openapi-zod-client/commit/a8e8ba7559904a93a604f680af7f6af99f01ff9a))
* export getOpenApiDependencyGraph ([25eb3e3](https://github.com/astahmer/openapi-zod-client/commit/25eb3e3f043075905e4f91a09b1a5d378c9d7aee))
* generate TS types so that z.lazy is typed properly ([635d0f5](https://github.com/astahmer/openapi-zod-client/commit/635d0f50d74bd634098c414ad096263a54e00d34))
* infer as object when type not set but properties/additionalProperties is ([bdb220b](https://github.com/astahmer/openapi-zod-client/commit/bdb220bee1a9f5706f0cbcf9051df3668676f80d))
* isMediaTypeAllowed option ([46bf611](https://github.com/astahmer/openapi-zod-client/commit/46bf6114ac918103fd082e37ff477aa0821bb3c7))
* mark recursive schemas with [@circular](https://github.com/circular) token ([1944f41](https://github.com/astahmer/openapi-zod-client/commit/1944f41e92649f8273b34abbfb39c07aef120c3f))
* openApiToTypescript with tanu.js ([b4f8352](https://github.com/astahmer/openapi-zod-client/commit/b4f835265257f2eea63ea2aaf8492e727b45833e))
* **openApiToTypescript:** handle additionalProperties ([101e1b0](https://github.com/astahmer/openapi-zod-client/commit/101e1b05310f3968f85b9bbe87459b024c96909b))
* string/number/array validations + format [#8](https://github.com/astahmer/openapi-zod-client/issues/8) + [#9](https://github.com/astahmer/openapi-zod-client/issues/9) ([e4d6354](https://github.com/astahmer/openapi-zod-client/commit/e4d6354cf3f63bd0e2f8a87181b05c610195073c))



