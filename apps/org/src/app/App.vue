<script setup lang="ts">
import NxWelcome from "./NxWelcome.vue";

interface Foo {
  name: string;
}

const sendMail = async () => {
  const mailData: Foo = {
    step1: "wouter",
  };

  return mailData;
};

sendMail();
</script>

<template>
  <NxWelcome title="@org/org" />
</template>
