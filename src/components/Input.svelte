<script>

    export let type = ''; 
    let state = true;
    
    
    </script>
    {#if type === 'password'}
        <div class="input-field">
            <label for="pass">Password (8 characters minimum):</label>
            <input type="password" id="pass" name="password"
                minlength="8" required>
        </div>
    {:else if type === 'email'}
        <div class="input-field">
            <label for="pass">Password (8 characters minimum):</label>
            <input type="password" id="pass" name="password"
                minlength="8" required>
        </div>
    {:else if type === 'simple'}
        <div class="input-field">
            <label for="pass">Password (8 characters minimum):</label>
            <input type="password" id="pass" name="password"
                minlength="8" required>
        </div>
    {/if}
    <style>
        .input-field {
            display: flex;
            flex-direction: column;
            text-align: left;
        }
    </style>