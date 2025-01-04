<script setup>
</script>

<template>
  <div class="commitItem">
    <div class="commit-header">
      <div class="user">
        <img class="avatar" src="./../images/placeholder.jpg" />
        <div class="user-name">
          <span>John Doe</span>
          <a class="user-profil" href="https://github.com/eliooooooo"><span>See github user</span>
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
              class="bi bi-box-arrow-up-right" viewBox="0 0 16 16">
              <path fill-rule="evenodd"
                d="M8.636 3.5a.5.5 0 0 0-.5-.5H1.5A1.5 1.5 0 0 0 0 4.5v10A1.5 1.5 0 0 0 1.5 16h10a1.5 1.5 0 0 0 1.5-1.5V7.864a.5.5 0 0 0-1 0V14.5a.5.5 0 0 1-.5.5h-10a.5.5 0 0 1-.5-.5v-10a.5.5 0 0 1 .5-.5h6.636a.5.5 0 0 0 .5-.5" />
              <path fill-rule="evenodd"
                d="M16 .5a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0 0 1h3.793L6.146 9.146a.5.5 0 1 0 .708.708L15 1.707V5.5a.5.5 0 0 0 1 0z" />
            </svg>
          </a>
        </div>
      </div>
      <div class="commit">
        <span class="commit-sha">9e40823</span>
        <span class="commit-date">2 days ago</span>
      </div>
    </div>
  </div>
</template>

<style>
.commit-header {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}

.avatar {
  border-radius: 999px;
  height: 70px;
}

.user {
  display: flex;
  flex-direction: row;
  gap: 20px
}

.user-name {
  display: flex;
  flex-direction: column;
  gap: 8px;
  font-size: larger;
}

.user-profil {
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 8px;
  color: lightslategray;
}

.commit {
  display: flex;
  flex-direction: column;
  gap: 8px;
  text-align: right;
}

.commit-sha {
  font-size: larger;
}

.commit-date {
  color: lightslategray;
}
</style>
