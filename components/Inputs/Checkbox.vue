  <template>
    <div class="flex items-center">
      <label class="block text-white text-sm font-bold mb-2">
        <slot name="label"></slot>
      </label>
        <input
          type="checkbox"
          class="form-input border border-gray-300 p-2 rounded-md text-sm focus:outline-none focus:border-indigo-500"
        />
        <p class="text-white text-base ml-2">
          <slot />
        </p>   
    </div>
  </template>
