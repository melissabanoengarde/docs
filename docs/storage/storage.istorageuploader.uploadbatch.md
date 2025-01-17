---
slug: /storage.istorageuploader.uploadbatch
title: IStorageUploader.uploadBatch() method
hide_title: true
displayed_sidebar: storage
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

# IStorageUploader.uploadBatch() method

Upload an array of arbitrary file data or JSON strings

**Signature:**

```typescript
uploadBatch(data: FileOrBufferOrString[], options?: T): Promise<string[]>;
```

## Parameters

| Parameter | Type                     | Description                                               |
| --------- | ------------------------ | --------------------------------------------------------- |
| data      | FileOrBufferOrString\[\] | Array of arbitrary file data or JSON strings to upload    |
| options   | T                        | <i>(Optional)</i> Options to pass through to the uploader |

**Returns:**

Promise&lt;string\[\]&gt;

Array of uploaded file URIs
