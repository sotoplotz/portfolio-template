# Content Collections and Typing Issues

## Problem

When typing content entries using `CollectionEntry<'news'>`,
TypeScript returned `never` and properties like `data`
were not accessible.

## Cause

Astro requires all content collections to be explicitly
defined in `src/content/config.ts`.

Having only folder structures is not enough for type inference.

## Solution

A content configuration file was added using
Astro’s official `defineCollection` API.

After defining the collection schema, TypeScript
was able to correctly infer content types.

A full restart of the development server was required
to regenerate the types.

## Key Learning

Astro content collections are strongly typed and require
explicit schema definitions to work correctly.
