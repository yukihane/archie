---
title: "Loose vs Tight List Rendering"
date: 2026-02-15T16:56:19+09:00
description: "List rendering examples covering paragraphs, wrapping, and nested lists."
tags: [css, markdown]
---

List markers should align with the first line of text. Loose lists should retain
paragraph spacing, and continuation lines should align with the item text.

## Tight list

- First item
- Second item

## Loose list

- First item

- Second item

## Wrapping

- A long list item with enough words to wrap across multiple lines on a narrow
  screen. Each continuation line should align with the first line of text.

- Another long item to check that paragraph spacing remains visible between
  items when their text wraps across multiple lines.

## Multiple paragraphs

- First paragraph of the first item.

  Second paragraph of the same item, aligned with the first paragraph.

- First paragraph of the second item.

## Nested lists

- Parent paragraph.

  - Nested first item.

  - Nested second item.

- Next parent paragraph.

## Ordered list inside an unordered list

- Parent paragraph.

  1. First ordered paragraph.

  2. Second ordered paragraph.

- Next parent paragraph.

## Blockquote and code

- First paragraph.

  > A blockquote after the first paragraph.

  ```text
  code after the paragraph
  ```

- Second item.
