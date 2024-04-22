---
layout: componentLayout
title: Svelte Timepicker - Flowbite
breadcrumb_title: Svelte Timepicker
component_title: Timepicker
dir: Experimental
description: Start receiving time data from your users using this free timepicker element based on Tailwind utility-classes and vanilla JavaScript
thumnailSize: w-28
---

<script>
  import { TableProp, TableDefaultRow, CompoAttributesViewer } from '../../utils'
  import { Alert } from '$lib'

  const components = 'Timepicker'
</script>

Time picker component

## Setup

```svelte example hideOutput
<script>
  import { Timepicker } from 'flowbite-svelte';
</script>
```

### Use rel="external"

This component is importing Flowbite datepicker javascript in the `svelte:head` section. When you are linking to a page using this component, use `rel="external"`.

## Datepicker example

Use the following example of an input element to create a datepicker component. All you need to do is to add the datepicker data attribute to any input element.

```svelte example
<script>
  import { Timepicker } from 'flowbite-svelte';
</script>

<Timepicker />
```

## Component data

The component has the following props, type, and default values. See [types page](/docs/pages/typescript) for type information.

<CompoAttributesViewer {components}/>