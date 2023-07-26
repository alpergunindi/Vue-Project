<template>
  <img :src="imageLink" class="h-8 w-8 rounded-3xl object-contain" alt="User profile image" />
</template>

<script>
export default {
  name: 'ProfileImage',
  data() {
    return {
      imageLink:
        'https://media.licdn.com/dms/image/C4D03AQFr-LCAux9grw/profile-displayphoto-shrink_800_800/0/1633371994961?e=1695254400&v=beta&t=VB3_Xe68xfuZdCi_usX8c9bPwdGgCAE_8UTDwX7HfeI'
    }
  }
}
</script>
