<template>
  <div
    class="flex justify-between items-center border-b-2 border-gray-100 py-6 md:justify-start md:space-x-10"
  >
    <div class="flex justify-start lg:w-0 lg:flex-1">
      <NuxtLink to="/">
        <img
          class="h-8 w-auto sm:h-10"
          src="/img/Hm-logo-04.png"
          alt="Hospital México"
        />
      </NuxtLink>
    </div>
    <div class="-mr-2 -my-2 md:hidden">
      <button
        type="button"
        class="bg-white rounded-md p-2 inline-flex items-center justify-center text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-indigo-500"
        aria-expanded="false"
      >
        <span class="sr-only">Open menu</span>
        <!-- Heroicon name: outline/menu -->
        <svg
          class="h-6 w-6"
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          aria-hidden="true"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16"
          />
        </svg>
      </button>
    </div>
    <nav class="hidden md:flex space-x-10">
      <Flyout title="Servicios">
        <DropdownLink to="test" title="Test" description="Test test test">
          <!-- Heroicon name: outline/chart-bar -->
          <svg
            class="flex-shrink-0 h-6 w-6 text-indigo-600"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            aria-hidden="true"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z"
            />
          </svg>
        </DropdownLink>
        <!--  <div
          class="px-5 py-5 bg-gray-50 space-y-6 sm:flex sm:space-y-0 sm:space-x-10 sm:px-8"
        >
          <div class="flow-root">
            <a
              href="#"
              class="-m-3 p-3 flex items-center rounded-md text-base font-medium text-gray-900 hover:bg-gray-100"
            >
              <svg
                class="flex-shrink-0 h-6 w-6 text-gray-400"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                aria-hidden="true"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M14.752 11.168l-3.197-2.132A1 1 0 0010 9.87v4.263a1 1 0 001.555.832l3.197-2.132a1 1 0 000-1.664z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
                />
              </svg>
              <span class="ml-3">Watch Demo</span>
            </a>
          </div>

          <div class="flow-root">
            <a
              href="#"
              class="-m-3 p-3 flex items-center rounded-md text-base font-medium text-gray-900 hover:bg-gray-100"
            >
              <svg
                class="flex-shrink-0 h-6 w-6 text-gray-400"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                aria-hidden="true"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"
                />
              </svg>
              <span class="ml-3">Contact Sales</span>
            </a>
          </div>
        </div> -->
      </Flyout>

      <NavLink to="test2" title="Test 2" />

      <Flyout title="Otros">
        <DropdownLink to="test2" title="Ayuda" description="Ayuda ayuda">
          <!-- Heroicon name: outline/support -->
          <svg
            class="flex-shrink-0 h-6 w-6 text-indigo-600"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            aria-hidden="true"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M18.364 5.636l-3.536 3.536m0 5.656l3.536 3.536M9.172 9.172L5.636 5.636m3.536 9.192l-3.536 3.536M21 12a9 9 0 11-18 0 9 9 0 0118 0zm-5 0a4 4 0 11-8 0 4 4 0 018 0z"
            />
          </svg>
        </DropdownLink>
        <div class="px-5 py-5 bg-gray-50 sm:px-8 sm:py-8">
          <div>
            <h3
              class="text-sm tracking-wide font-medium text-gray-500 uppercase"
            >
              Recent Posts
            </h3>
            <ul class="mt-4 space-y-4">
              <li class="text-base truncate">
                <a
                  href="#"
                  class="font-medium text-gray-900 hover:text-gray-700"
                >
                  Boost your conversion rate
                </a>
              </li>

              <li class="text-base truncate">
                <a
                  href="#"
                  class="font-medium text-gray-900 hover:text-gray-700"
                >
                  How to use search engine optimization to drive traffic to your
                  site
                </a>
              </li>

              <li class="text-base truncate">
                <a
                  href="#"
                  class="font-medium text-gray-900 hover:text-gray-700"
                >
                  Improve your customer experience
                </a>
              </li>
            </ul>
          </div>
          <div class="mt-5 text-sm">
            <a
              href="#"
              class="font-medium text-indigo-600 hover:text-indigo-500"
            >
              View all posts <span aria-hidden="true">&rarr;</span></a
            >
          </div>
        </div>
      </Flyout>
    </nav>
    <div class="hidden md:flex items-center justify-end md:flex-1 lg:w-0">
      <a
        href="#"
        class="whitespace-nowrap text-base font-medium text-gray-500 hover:text-gray-900"
      >
        Sign in
      </a>
      <a
        href="#"
        class="ml-8 whitespace-nowrap inline-flex items-center justify-center px-4 py-2 border border-transparent rounded-md shadow-sm text-base font-medium text-white bg-indigo-600 hover:bg-indigo-700"
      >
        Sign up
      </a>
    </div>
  </div>
</template>
<script>
import DropdownLink from './DropdownLink'
import NavLink from './NavLink'
import Flyout from './Flyout'
export default {
  name: 'Header',
  components: {
    DropdownLink,
    NavLink,
    Flyout,
  },
}
</script>
