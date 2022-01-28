<script setup lang="ts">
import { HasID } from "../types.js";
import { makeProfile } from "../constructors.js";

const Bar: HasID = { _id: "bar1" }
makeProfile();
console.log(Bar);
</script>

<template>Bar</template>
