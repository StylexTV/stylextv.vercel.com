<template>
  <AppContentItem class="w-full h-20 !max-w-none !mx-0 !py-0 grid grid-cols-3 bg-gray-900 border-b-2 border-gray-800" showImmediately>
    <AppHeaderLogo/>

    <AppHeaderNavbar>
      <AppHeaderNavbarItem linkTo="/">Start</AppHeaderNavbarItem>
      <AppHeaderNavbarItem linkTo="/blog">Blog</AppHeaderNavbarItem>
      <AppHeaderNavbarItem linkTo="/design">Design</AppHeaderNavbarItem>
    </AppHeaderNavbar>

    <AppHeaderSocials>
      <AppHeaderSocialsItem iconName="twitter" linkTo="https://twitter.com"/>
      <AppHeaderSocialsItem iconName="discord" linkTo="https://discord.com"/>
      <AppHeaderSocialsItem iconName="github" linkTo="https://github.com"/>
    </AppHeaderSocials>
  </AppContentItem>
</template>
