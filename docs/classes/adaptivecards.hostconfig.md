[Adaptive Cards Javascript SDK](../README.md) / [adaptivecards](../modules/adaptivecards.md) / HostConfig

# Class: HostConfig

[adaptivecards](../modules/adaptivecards.md).HostConfig

## Table of contents

### Constructors

- [constructor](adaptivecards.hostconfig.md#constructor)

### Properties

- [actions](adaptivecards.hostconfig.md#actions)
- [adaptiveCard](adaptivecards.hostconfig.md#adaptivecard)
- [alwaysAllowBleed](adaptivecards.hostconfig.md#alwaysallowbleed)
- [choiceSetInputValueSeparator](adaptivecards.hostconfig.md#choicesetinputvalueseparator)
- [containerStyles](adaptivecards.hostconfig.md#containerstyles)
- [cssClassNamePrefix](adaptivecards.hostconfig.md#cssclassnameprefix)
- [factSet](adaptivecards.hostconfig.md#factset)
- [fontTypes](adaptivecards.hostconfig.md#fonttypes)
- [hostCapabilities](adaptivecards.hostconfig.md#hostcapabilities)
- [imageSet](adaptivecards.hostconfig.md#imageset)
- [imageSizes](adaptivecards.hostconfig.md#imagesizes)
- [inputs](adaptivecards.hostconfig.md#inputs)
- [lineHeights](adaptivecards.hostconfig.md#lineheights)
- [media](adaptivecards.hostconfig.md#media)
- [separator](adaptivecards.hostconfig.md#separator)
- [spacing](adaptivecards.hostconfig.md#spacing)
- [supportsInteractivity](adaptivecards.hostconfig.md#supportsinteractivity)

### Accessors

- [fontFamily](adaptivecards.hostconfig.md#fontfamily)
- [fontSizes](adaptivecards.hostconfig.md#fontsizes)
- [fontWeights](adaptivecards.hostconfig.md#fontweights)

### Methods

- [getEffectiveSpacing](adaptivecards.hostconfig.md#geteffectivespacing)
- [getFontTypeDefinition](adaptivecards.hostconfig.md#getfonttypedefinition)
- [makeCssClassName](adaptivecards.hostconfig.md#makecssclassname)
- [makeCssClassNames](adaptivecards.hostconfig.md#makecssclassnames)
- [paddingDefinitionToSpacingDefinition](adaptivecards.hostconfig.md#paddingdefinitiontospacingdefinition)

## Constructors

### constructor

\+ **new HostConfig**(`obj?`: *any*): [*HostConfig*](host_config.hostconfig.md)

#### Parameters:

Name | Type |
:------ | :------ |
`obj?` | *any* |

**Returns:** [*HostConfig*](host_config.hostconfig.md)

Defined in: [host-config.ts:591](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L591)

## Properties

### actions

??? `Readonly` **actions**: [*ActionsConfig*](host_config.actionsconfig.md)

Defined in: [host-config.ts:584](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L584)

___

### adaptiveCard

??? `Readonly` **adaptiveCard**: [*AdaptiveCardConfig*](host_config.adaptivecardconfig.md)

Defined in: [host-config.ts:585](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L585)

___

### alwaysAllowBleed

??? **alwaysAllowBleed**: *boolean*= false

Defined in: [host-config.ts:591](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L591)

___

### choiceSetInputValueSeparator

??? **choiceSetInputValueSeparator**: *string*= ","

Defined in: [host-config.ts:557](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L557)

___

### containerStyles

??? `Readonly` **containerStyles**: [*ContainerStyleSet*](host_config.containerstyleset.md)

Defined in: [host-config.ts:582](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L582)

___

### cssClassNamePrefix

??? `Optional` **cssClassNamePrefix**: *undefined* \| *string*

Defined in: [host-config.ts:590](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L590)

___

### factSet

??? `Readonly` **factSet**: [*FactSetConfig*](host_config.factsetconfig.md)

Defined in: [host-config.ts:588](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L588)

___

### fontTypes

??? `Optional` **fontTypes**: *undefined* \| [*FontTypeSet*](host_config.fonttypeset.md)

Defined in: [host-config.ts:560](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L560)

___

### hostCapabilities

??? `Readonly` **hostCapabilities**: [*HostCapabilities*](host_capabilities.hostcapabilities.md)

Defined in: [host-config.ts:553](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L553)

___

### imageSet

??? `Readonly` **imageSet**: [*ImageSetConfig*](host_config.imagesetconfig.md)

Defined in: [host-config.ts:586](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L586)

___

### imageSizes

??? `Readonly` **imageSizes**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`large` | *number* |
`medium` | *number* |
`small` | *number* |

Defined in: [host-config.ts:576](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L576)

___

### inputs

??? `Readonly` **inputs**: [*InputConfig*](host_config.inputconfig.md)

Defined in: [host-config.ts:583](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L583)

___

### lineHeights

??? `Optional` **lineHeights**: *undefined* \| [*ILineHeightDefinitions*](../interfaces/host_config.ilineheightdefinitions.md)

Defined in: [host-config.ts:559](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L559)

___

### media

??? `Readonly` **media**: [*MediaConfig*](host_config.mediaconfig.md)

Defined in: [host-config.ts:587](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L587)

___

### separator

??? `Readonly` **separator**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`lineColor` | *string* |
`lineThickness` | *number* |

Defined in: [host-config.ts:571](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L571)

___

### spacing

??? `Readonly` **spacing**: *object*

#### Type declaration:

Name | Type |
:------ | :------ |
`default` | *number* |
`extraLarge` | *number* |
`large` | *number* |
`medium` | *number* |
`padding` | *number* |
`small` | *number* |

Defined in: [host-config.ts:562](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L562)

___

### supportsInteractivity

??? **supportsInteractivity**: *boolean*= true

Defined in: [host-config.ts:558](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L558)

## Accessors

### fontFamily

??? get **fontFamily**(): *undefined* \| *string*

**Returns:** *undefined* \| *string*

Defined in: [host-config.ts:700](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L700)

??? set **fontFamily**(`value`: *undefined* \| *string*): *void*

#### Parameters:

Name | Type |
:------ | :------ |
`value` | *undefined* \| *string* |

**Returns:** *void*

Defined in: [host-config.ts:704](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L704)

___

### fontSizes

??? get **fontSizes**(): [*IFontSizeDefinitions*](../interfaces/host_config.ifontsizedefinitions.md)

**Returns:** [*IFontSizeDefinitions*](../interfaces/host_config.ifontsizedefinitions.md)

Defined in: [host-config.ts:708](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L708)

___

### fontWeights

??? get **fontWeights**(): [*IFontWeightDefinitions*](../interfaces/host_config.ifontweightdefinitions.md)

**Returns:** [*IFontWeightDefinitions*](../interfaces/host_config.ifontweightdefinitions.md)

Defined in: [host-config.ts:712](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L712)

## Methods

### getEffectiveSpacing

??? **getEffectiveSpacing**(`spacing`: [*Spacing*](../enums/enums.spacing.md)): *number*

#### Parameters:

Name | Type |
:------ | :------ |
`spacing` | [*Spacing*](../enums/enums.spacing.md) |

**Returns:** *number*

Defined in: [host-config.ts:657](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L657)

___

### getFontTypeDefinition

??? **getFontTypeDefinition**(`style?`: [*Default*](../enums/enums.fonttype.md#default) \| [*Monospace*](../enums/enums.fonttype.md#monospace)): [*FontTypeDefinition*](host_config.fonttypedefinition.md)

#### Parameters:

Name | Type |
:------ | :------ |
`style?` | [*Default*](../enums/enums.fonttype.md#default) \| [*Monospace*](../enums/enums.fonttype.md#monospace) |

**Returns:** [*FontTypeDefinition*](host_config.fonttypedefinition.md)

Defined in: [host-config.ts:648](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L648)

___

### makeCssClassName

??? **makeCssClassName**(...`classNames`: *string*[]): *string*

#### Parameters:

Name | Type |
:------ | :------ |
`...classNames` | *string*[] |

**Returns:** *string*

Defined in: [host-config.ts:694](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L694)

___

### makeCssClassNames

??? **makeCssClassNames**(...`classNames`: *string*[]): *string*[]

#### Parameters:

Name | Type |
:------ | :------ |
`...classNames` | *string*[] |

**Returns:** *string*[]

Defined in: [host-config.ts:684](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L684)

___

### paddingDefinitionToSpacingDefinition

??? **paddingDefinitionToSpacingDefinition**(`paddingDefinition`: [*PaddingDefinition*](shared.paddingdefinition.md)): [*SpacingDefinition*](shared.spacingdefinition.md)

#### Parameters:

Name | Type |
:------ | :------ |
`paddingDefinition` | [*PaddingDefinition*](shared.paddingdefinition.md) |

**Returns:** [*SpacingDefinition*](shared.spacingdefinition.md)

Defined in: [host-config.ts:676](https://github.com/microsoft/AdaptiveCards/blob/0938a1f10/source/nodejs/adaptivecards/src/host-config.ts#L676)
