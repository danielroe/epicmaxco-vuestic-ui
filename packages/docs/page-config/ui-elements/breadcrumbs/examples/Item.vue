<template>
  <va-breadcrumbs>
    <va-breadcrumbs-item label="One" />
    <va-breadcrumbs-item
      label="Two"
      to="/"
      disabled
    />
    <va-breadcrumbs-item
      label="Three"
      to="#examples"
    />
    <va-breadcrumbs-item label="Four" />
    <va-breadcrumbs-item label="Five">
      <span class="italic text-[var(--va-danger)]">
        Slotted content</span>
    </va-breadcrumbs-item>
  </va-breadcrumbs>
</template>
