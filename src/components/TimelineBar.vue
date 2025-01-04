<script setup>
import CommitItem from './CommitItem.vue';

</script>

<template>
  <div class="history-container">
    <div class="history-item">
      <div class="history-line">
        <div class="line-round"></div>
        <div class="line-line"></div>
      </div>
      <div class="history-content">
        <CommitItem />
        <p class="placeholder"></p>
      </div>
    </div>
  </div>
</template>

<style>
.history-container {
  display: flex;
  flex-direction: column;
  padding: 5px 30px;
}

.history-item {
  display: flex;
  flex-direction: row;
  gap: 30px;
}

.history-line {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 20px;
}

.line-round {
  width: 30px;
  height: 30px;
  border-radius: 999px;
  background-color: #7162d1;
}

.line-line {
  width: 10px;
  min-height: 10px;
  height: 100%;
  border-radius: 999px;
  background-color: #7162d1;
}

.history-content {
  width: 100%;
}

.placeholder {
  height: 1000px;
}
</style>
