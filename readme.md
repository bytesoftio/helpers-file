# @bytesoftio/helpers-file

## Installation

`yarn add @bytesoftio/helpers-file` or `npm install @bytesoftio/helpers-file`

## Table of contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Description](#description)
- [Usage](#usage)
  - [downloadAsFile](#downloadasfile)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Description

Collection of file related helpers.

## Usage

### downloadAsFile

Download any kind of data as a file (works only in browser).

```ts
import { downloadAsFile } from "@bytesoftio/helpers-file"

const fileName = "data.csv"
const data = "name,age\nJohn,30\nSnow,40"

downloadAsFile(fileName, data)
```


