<script lang="ts">
    import UILayout from "./UILayout.svelte";
</script>

<UILayout title="HabiDemo">
    <div class="card">
        <p>List 1</p>
        <p>List 2</p>
        <p>List 3</p>
        <p>List 4</p>
        <p>List 5</p>
    </div>
    
    <div class="card">
        <p>Water</p>
    </div>

    <div class="card">
        <p>Condition</p>
    </div>

    <div class="card">
        <p>Date</p>
    </div>

    <div class="card">
        <p>Remind Later</p>
    </div>
</UILayout>

<style>
    .card {
        background-color: white;
        border-radius: 18px;
        padding: 20px 24px;
        margin-bottom: 16px;
        box-shadow: 0 2px 10px rgba(0, 0, 0, 0.03);
        font-size: 1.1rem;
        font-weight: 500;
        color: #1c1c1e;
    }
</style>
