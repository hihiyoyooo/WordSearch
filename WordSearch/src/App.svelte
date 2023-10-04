<script>
  import Routes from "svelte-spa-router";
  import Home from "./pages/Home.svelte";

  const routes = {
    "/": Home,
  };
</script>

<Routes {routes} />
