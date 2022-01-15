<template>
  <section>
    <header>
      <h1>My Friends</h1>
    </header>
    <ul>
      <friend-contact
        name="shivam sharma"
        phone-number="0123 4567 890"
        email-address="shiva@gmail.com "
        hobby="playing"
      >
      </friend-contact>
      <friend-contact
        name="sanjana sharma"
        phone-number="0433 4537 840"
        email-address="sanjana@gmail.com"
        hobby="fighting"
      >
      </friend-contact>
    </ul>
  </section>
</template>

<script>
import FriendContact from "./components/FriendContact.vue";
export default {
  components: { FriendContact },
  data() {
    return {
      friends: [
        // {
        //   id: "shiv",
        //   name: "shiv sharma",
        //   phone: "0123  4567 890",
        //   email: "shiva@gmail.com",
        // },
        // {
        //   id: "sanjana",
        //   name: "sanjana sharma",
        //   phone: "0433  4537 840",
        //   email: "sanjana@gmail.com",
        // },
      ],
    };
  },
};
</script>