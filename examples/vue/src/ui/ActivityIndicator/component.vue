<script lang="ts" setup>

</script>

<template>
  <Page>
    <GridLayout>
      <!-- Actual example shown in code examples/used in apps. -->
      <ContentView verticalAlignment="center" horizontalAlignment="center" android:visibility="collapse">
        <!-- #region example -->
        <ActivityIndicator busy="true" />
        <!-- #endregion example -->
      </ContentView>

      <!-- "Fake" indicator for android screenshots  -->
      <GridLayout ios:visibility="collapse" verticalAlignment="center" horizontalAlignment="center">
        <ContentView
            width="40" height="40"
            borderRadius="50"
            borderWidth="4" borderColor="#65adf1"
        />
        <ContentView
            width="40" height="40"
            translateX="-20"
            translateY="-20"
            backgroundColor="white" />
      </GridLayout>
    </GridLayout>

  </Page>
</template>
