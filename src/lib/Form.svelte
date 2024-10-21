<script>
    import Button from "$lib/Button.svelte";
  
    let name, email, password1, password2 = "";
  </script>

<form class="m-auto mt-12 flex flex-col w-[45%]" id="data-form" action="POST">
    <label class="font-bold text-[16px] mb-1" for="user-name">Name</label>
    <input class="border border-[#00000099] rounded-[8px] mb-8 pl-2 h-[2.3em]" type="text" id="user-name" bind:value={name} placeholder="Enter your name"
    />
  
    <label class="font-bold text-[16px] mb-1" for="user-email">Email</label>
    <input class="border border-[#00000099] rounded-[8px] mb-8 pl-2 h-[2.3em]" type="email" id="user-email" bind:value={email} placeholder="Enter your email"
    />
  
    <label class="font-bold text-[16px] mb-1" for="user-password1">Password</label>
    <input class="border border-[#00000099] rounded-[8px] mb-8 pl-2 h-[2.3em]" type="password" id="user-password1" bind:value={password1} placeholder="Enter your password"
    />
  
    <label class="font-bold text-[16px] mb-1" for="user-password2">Re-enter password</label>
    <input class="border border-[#00000099] rounded-[8px] mb-8 pl-2 h-[2.3em]" type="password" id="user-password2" bind:value={password2} placeholder="Re-enter your password"
    />
  
    <Button label="Send your data" />
  </form>