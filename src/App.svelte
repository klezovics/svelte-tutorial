<script lang="ts">
    import svelteLogo from './assets/svelte.svg'
    import Counter from './lib/Counter.svelte'
    import MyFirstComponent from "./lib/1_hello_svelte/MyFirstComponent.svelte";
    import ComponentWithProps from "./lib/2_component_props/ComponentWithProps.svelte";
    import ComponentWithState from "./lib/3_component_state/ComponentWithState.svelte";
    import ContainerComponent from "./lib/4_component_composition/ContainerComponent.svelte";
    import MyComponentWithJs from "./lib/1_hello_svelte/MyComponentWithJs.svelte";
    import MyComponentWithCss from "./lib/1_hello_svelte/MyComponentWithCss.svelte";
    import ComponentWithBasicReactivity from "./lib/5_reactivity/ComponentWithBasicReactivity.svelte";
    import ComponentWithReactiveDeclarations from "./lib/5_reactivity/ComponentWithReactiveDeclarations.svelte";
    import ComponentWithReactiveStatements from "./lib/5_reactivity/ComponentWithReactiveStatements.svelte";
</script>

<main>
    <!--    Section 1 -->
    <!--    <MyFirstComponent />-->
    <!--    <MyComponentWithJs/>-->
    <!--    <MyComponentWithCss/>-->


    <!--    Section 2 -->
    <!--    <ComponentWithProps name="John" surname="Dow"/>-->
    <!--    <ComponentWithProps />-->
    <!--    <ComponentWithProps name="John"/>-->
    <!--    <ComponentWithProps surname="Dow"/>-->

    <!--    Section 3 -->
    <!--    <ComponentWithState />-->

    <!--    Section 4 -->
    <!--    <ContainerComponent />-->

    <!--    Section 5 -->
    <ComponentWithBasicReactivity />
    <ComponentWithReactiveDeclarations />
    <ComponentWithReactiveStatements />


</main>

<style>
</style>
