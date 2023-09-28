<template>
  <div>
    <!--heder-->
    <Topheadr />
    <div class="container lg:grid lg:grid-cols-12 lg:gap-10">
      <!--sidbar-->
      <Sidbar  class="hidden lg:col-span-3 lg:block"/>
      

      <!--minsection-->
      <main class="py-5 lg:col-span-6">

        <!--status-->
        <StatusCard/>

        <!--Custom list-->
        <NewCustomers />
        <!-- Charts -->
        <SalesChart />
        <!-- Recent orders -->
        <RecentOrders />
      </main>

      <div>
         <!--Profile-->
         <ProfileInfo />
        <hr class="my-5" />
        <!-- Reminders to the side -->
        <Reminders />
      </div>
    </div>
  </div>
</template>
