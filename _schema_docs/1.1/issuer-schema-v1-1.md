---
title: Issuer Schema Version 1.1
sitemap: true
permalink: /docs/schema/v1_1/issuer_schema/
---

The schema defines the following properties:

## `issuer_key` (array, required)

The object is an array with all elements of the type `object`.

The array object has the following properties:

### `date` (string, required)

Date time ISO-8601 format of the date that the keys were issued.

### `key` (string, required)

Bitcoin address (compressed public key, usually 24 characters) that the issuer uses to issue the certificates.

## `revocation_key` (array, required)

The object is an array with all elements of the type `object`.

The array object has the following properties:

### `date` (string, required)

Date time ISO-8601 format of the date that the keys were issued.

### `key` (string, required)

Bitcoin address (compressed public key, usually 24 characters) that the issuer uses to revoke the certificates.