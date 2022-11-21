<script setup>
import { ElTable, ElTableColumn } from "element-plus";

const tableData = [
  {
    date: "2016-05-03",
    name: "Christopher",
    address: "No. 189, Grove St, Los Angeles",
  },
  {
    date: "2016-05-02",
    name: "Christopher",
    address: "No. 189, Grove St, Los Angeles",
  },
  {
    date: "2016-05-04",
    name: "Christopher",
    address: "No. 189, Grove St, Los Angeles",
  },
  {
    date: "2016-05-01",
    name: "Christopher",
    address: "No. 189, Grove St, Los Angeles",
  },
];
</script>

<template>
  <el-table :data="tableData" border style="width: 100%">
    <el-table-column prop="date" label="Date" width="90" />
    <el-table-column prop="name" label="Name" width="90" />
    <el-table-column prop="address" label="Address" />
  </el-table>
</template>

<style scoped></style>
