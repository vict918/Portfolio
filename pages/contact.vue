<template>
    <div>
        <div class="contact">
            <div class="contact__list">
                <div class="contact__email">
                    <i class="fas fa-envelope"></i> Email
                    <div class="text-secondary">email@email.com</div>
                    </div>
                    <div class="contact__phone">
                    <i class="fas fa-mobile-alt"></i> Phone
                    <div class="text-secondary">+32 478 66 26 07</div>
                    </div>
                    <div class="contact__address">
                    <i class="fas fa-map-marker-alt"></i> Address
                    <div class="text-secondary">Mont-Saint-Guibert</div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  head: {
    title: 'Contact',
    meta: [
      {
        hid: 'description',
        name: 'description',
        content: 'Contact Victor Cotton'
      }
    ],
  }
}
</script>

<style lang="scss" scoped>

</style>