---
title: "danog\\Decoder\\FileIdType: Represents decoded bot API file ID type."
description: ""

---
# `danog\Decoder\FileIdType`
[Back to index](../../index.md)

> Author: Daniil Gentili <daniil@daniil.it>  
  

Represents decoded bot API file ID type.  




## Constants
* `danog\Decoder\FileIdType::THUMBNAIL`: Thumbnail.

* `danog\Decoder\FileIdType::PROFILE_PHOTO`: Profile photo.
  
  Used for users and channels, chat photos are normal PHOTOs.

* `danog\Decoder\FileIdType::PHOTO`: Normal photos.

* `danog\Decoder\FileIdType::VOICE`: Voice messages.

* `danog\Decoder\FileIdType::VIDEO`: Video.

* `danog\Decoder\FileIdType::DOCUMENT`: Document.

* `danog\Decoder\FileIdType::ENCRYPTED`: Secret chat document.

* `danog\Decoder\FileIdType::TEMP`: Temporary document.

* `danog\Decoder\FileIdType::STICKER`: Sticker.

* `danog\Decoder\FileIdType::AUDIO`: Music.

* `danog\Decoder\FileIdType::ANIMATION`: GIF.

* `danog\Decoder\FileIdType::ENCRYPTED_THUMBNAIL`: Encrypted thumbnail.

* `danog\Decoder\FileIdType::WALLPAPER`: Wallpaper.

* `danog\Decoder\FileIdType::VIDEO_NOTE`: Round video.

* `danog\Decoder\FileIdType::SECURE_RAW`: Passport raw file.

* `danog\Decoder\FileIdType::SECURE`: Passport file.

* `danog\Decoder\FileIdType::BACKGROUND`: Background.

* `danog\Decoder\FileIdType::SIZE`: Size.

## Properties
* `$name`: `string` 
* `$value`: `int` 

## Method list:
* [`fromBotApiType(string $type): self`](#frombotapitype-string-type-self)
* [`toBotApiType(): string`](#tobotapitype-string)
* [`toUnique(): \danog\Decoder\UniqueFileIdType`](#tounique-danog-decoder-uniquefileidtype)
* [`cases(): array`](#cases-array)
* [`from(string|int $value): static`](#from-string-int-value-static)
* [`tryFrom(string|int $value): ?static`](#tryfrom-string-int-value-static)

## Methods:
### `fromBotApiType(string $type): self`

Obtain a FileId enum variant from a bot API type name.


Parameters:

* `$type`: `string`   



### `toBotApiType(): string`

Obtain a bot API type name.



### `toUnique(): \danog\Decoder\UniqueFileIdType`

Convert file ID type to unique file ID type.


#### See also: 
* [`\danog\Decoder\UniqueFileIdType`: Represents decoded unique bot API file ID type.](../../danog/Decoder/UniqueFileIdType.md)




### `cases(): array`





### `from(string|int $value): static`




Parameters:

* `$value`: `string|int`   



### `tryFrom(string|int $value): ?static`




Parameters:

* `$value`: `string|int`   



---
Generated by [danog/phpdoc](https://phpdoc.daniil.it)