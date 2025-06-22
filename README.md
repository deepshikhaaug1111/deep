# deep
<html>
  <head>
    <link rel="preconnect" href="https://fonts.gstatic.com/" crossorigin="" />
    <link
      rel="stylesheet"
      as="style"
      onload="this.rel='stylesheet'"
      href="https://fonts.googleapis.com/css2?display=swap&amp;family=Newsreader%3Awght%40400%3B500%3B700%3B800&amp;family=Noto+Sans%3Awght%40400%3B500%3B700%3B900"
    />

    <title>Stitch Design</title>
    <link rel="icon" type="image/x-icon" href="data:image/x-icon;base64," />

    <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
  </head>
  <body>
    <div class="relative flex size-full min-h-screen flex-col bg-white group/design-root overflow-x-hidden" style='font-family: Newsreader, "Noto Sans", sans-serif;'>
      <div class="layout-container flex h-full grow flex-col">
        <header class="flex items-center justify-between whitespace-nowrap border-b border-solid border-b-[#f0f2f4] px-10 py-3">
          <div class="flex items-center gap-4 text-[#111418]">
            <div class="size-4">
              <svg viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                  d="M24 45.8096C19.6865 45.8096 15.4698 44.5305 11.8832 42.134C8.29667 39.7376 5.50128 36.3314 3.85056 32.3462C2.19985 28.361 1.76794 23.9758 2.60947 19.7452C3.451 15.5145 5.52816 11.6284 8.57829 8.5783C11.6284 5.52817 15.5145 3.45101 19.7452 2.60948C23.9758 1.76795 28.361 2.19986 32.3462 3.85057C36.3314 5.50129 39.7376 8.29668 42.134 11.8833C44.5305 15.4698 45.8096 19.6865 45.8096 24L24 24L24 45.8096Z"
                  fill="currentColor"
                ></path>
              </svg>
            </div>
            <h2 class="text-[#111418] text-lg font-bold leading-tight tracking-[-0.015em]">Inkwell</h2>
          </div>
          <div class="flex flex-1 justify-end gap-8">
            <div class="flex items-center gap-9">
              <a class="text-[#111418] text-sm font-medium leading-normal" href="#">Home</a>
              <a class="text-[#111418] text-sm font-medium leading-normal" href="#">Fiction</a>
              <a class="text-[#111418] text-sm font-medium leading-normal" href="#">Poetry</a>
              <a class="text-[#111418] text-sm font-medium leading-normal" href="#">Essays</a>
              <a class="text-[#111418] text-sm font-medium leading-normal" href="#">Reviews</a>
              <a class="text-[#111418] text-sm font-medium leading-normal" href="#">About</a>
            </div>
            <div class="flex gap-2">
              <button
                class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-lg h-10 px-4 bg-[#f0f2f4] text-[#111418] text-sm font-bold leading-normal tracking-[0.015em]"
              >
                <span class="truncate">Subscribe</span>
              </button>
              <button
                class="flex max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-lg h-10 bg-[#f0f2f4] text-[#111418] gap-2 text-sm font-bold leading-normal tracking-[0.015em] min-w-0 px-2.5"
              >
                <div class="text-[#111418]" data-icon="MagnifyingGlass" data-size="20px" data-weight="regular">
                  <svg xmlns="http://www.w3.org/2000/svg" width="20px" height="20px" fill="currentColor" viewBox="0 0 256 256">
                    <path
                      d="M229.66,218.34l-50.07-50.06a88.11,88.11,0,1,0-11.31,11.31l50.06,50.07a8,8,0,0,0,11.32-11.32ZM40,112a72,72,0,1,1,72,72A72.08,72.08,0,0,1,40,112Z"
                    ></path>
                  </svg>
                </div>
              </button>
            </div>
          </div>
        </header>
        <div class="px-40 flex flex-1 justify-center py-5">
          <div class="layout-content-container flex flex-col max-w-[960px] flex-1">
            <div class="@container">
              <div class="@[480px]:p-4">
                <div
                  class="flex min-h-[480px] flex-col gap-6 bg-cover bg-center bg-no-repeat @[480px]:gap-8 @[480px]:rounded-lg items-center justify-center p-4"
                  style='background-image: linear-gradient(rgba(0, 0, 0, 0.1) 0%, rgba(0, 0, 0, 0.4) 100%), url("https://lh3.googleusercontent.com/aida-public/AB6AXuBJTGKZSDDoXVKtNJQ7nWgawV1DuDVE4D0tqPYnB_O5lAaVRCxA0tmS1dGjkk1bnovHEAuIrkdOUHglD2LGPHJifvJEq-3D1RDEqtzUOItt6YPnawFmdvGmTtcCbBrVO9yvLubRduLlD4d3lmtQ2m0zeRz32hMPoKLX0Tm82ABkwEMuqvia9NHW8nFdAlbEIYpr5Q_Ivzt0Qjk5tahqeTsfMGMGIvnuCSZrAaMbsJ3lwrkz7-OZn1-ZNx6FXoO1AVbssGBgMH1H_Cc");'
                >
                  <div class="flex flex-col gap-2 text-center">
                    <h1
                      class="text-white text-4xl font-black leading-tight tracking-[-0.033em] @[480px]:text-5xl @[480px]:font-black @[480px]:leading-tight @[480px]:tracking-[-0.033em]"
                    >
                      Inkwell
                    </h1>
                    <h2 class="text-white text-sm font-normal leading-normal @[480px]:text-base @[480px]:font-normal @[480px]:leading-normal">
                      A literary magazine for the curious mind.
                    </h2>
                  </div>
                  <button
                    class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-lg h-10 px-4 @[480px]:h-12 @[480px]:px-5 bg-[#1672ce] text-white text-sm font-bold leading-normal tracking-[0.015em] @[480px]:text-base @[480px]:font-bold @[480px]:leading-normal @[480px]:tracking-[0.015em]"
                  >
                    <span class="truncate">Explore</span>
                  </button>
                </div>
              </div>
            </div>
            <h2 class="text-[#111418] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5">Featured</h2>
            <div class="p-4 @container">
              <div class="flex flex-col items-stretch justify-start rounded-lg @xl:flex-row @xl:items-start">
                <div
                  class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-lg"
                  style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuAwRzC8lAgjqb34CKVrVmJypglmxPPTiDPhEpxrqzgzAvP66D-55W0OMDGKk-wHRuh4bPSLNys2M4zyw0kM5csG9SZ9SNrRdIMQk51PHfhBk3Fdu6A5Cy4LbceMw551JJNQkwvU-5iwmIH7lMynKpuAJivqOXs4Hg9eKBdThTgr4A875zVihrj2qqh-CvY-vzmrP73jp3ZC-y9I-Yz1sRvbOGivCHAN9JsUV-pUzI1jphkQvp4JOetb5YtQodGoBHxQLPFQoWU4oYk");'
                ></div>
                <div class="flex w-full min-w-72 grow flex-col items-stretch justify-center gap-1 py-4 @xl:px-4">
                  <p class="text-[#111418] text-lg font-bold leading-tight tracking-[-0.015em]">The Whispering Woods</p>
                  <div class="flex items-end gap-3 justify-between">
                    <p class="text-[#637588] text-base font-normal leading-normal">A short story by Amelia Hayes</p>
                    <button
                      class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-lg h-8 px-4 bg-[#1672ce] text-white text-sm font-medium leading-normal"
                    >
                      <span class="truncate">Read Now</span>
                    </button>
                  </div>
                </div>
              </div>
            </div>
            <h2 class="text-[#111418] text-[22px] font-bold leading-tight tracking-[-0.015em] px-4 pb-3 pt-5">Recent Articles</h2>
            <div class="p-4">
              <div class="flex items-stretch justify-between gap-4 rounded-lg">
                <div class="flex flex-col gap-1 flex-[2_2_0px]">
                  <p class="text-[#111418] text-base font-bold leading-tight">The Poet's Muse</p>
                  <p class="text-[#637588] text-sm font-normal leading-normal">An essay on inspiration</p>
                </div>
                <div
                  class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-lg flex-1"
                  style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuBLBPND-pfFxgzFcdgSBw3Thgh0Vgt39wBYfJN6HqpLHA3B6XXq3zEu6dXmZnVV7IY1pXR7c7QGlipsW21jJQSluu7cNCfuATP07B4KnktOnzZVsuwkcDsr30fNnIvFjDPG6MjdmVmXcjRslc4gyYddrzYFTdEUdKpqO2tuPhf3Ikuu-WZI0a1RrZO2Q7hWgiATgOhrLjAdVvcH0ztPy7zlJk_QItlNOrO8v9WBTJotH0f56P59QIMqhpCwfpcr9fnmOeNozi3aCbE");'
                ></div>
              </div>
            </div>
            <div class="p-4">
              <div class="flex items-stretch justify-between gap-4 rounded-lg">
                <div class="flex flex-col gap-1 flex-[2_2_0px]">
                  <p class="text-[#111418] text-base font-bold leading-tight">Review: The Silent Stream</p>
                  <p class="text-[#637588] text-sm font-normal leading-normal">A novel review by Ethan Clark</p>
                </div>
                <div
                  class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-lg flex-1"
                  style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuDxRa0YI6O7zPUjnx0aOqFxGJz_6uifgr5OkEmLSMcjaXZxcL384CuzxGRaY7oIyaQxu0m59zD00vD9wzv7P8_2PahKrq5HxcTAtndmn8EHyUwmiztmCWMW3iLUJnHpqDLREMMfS2NPdgF3cMkrxFrHbeEzS_rnW0HSJJQasYoR8sy4zTKZFmGn9tuJldKE6nVIri_b6emwnkb2qgOXmawvVlgsLBiPhJwpl0FZWqZG9SiJMlohmZhC4pf5IsTxCxGCtP1L19mK-HE");'
                ></div>
              </div>
            </div>
            <div class="p-4">
              <div class="flex items-stretch justify-between gap-4 rounded-lg">
                <div class="flex flex-col gap-1 flex-[2_2_0px]">
                  <p class="text-[#111418] text-base font-bold leading-tight">The Wanderer's Song</p>
                  <p class="text-[#637588] text-sm font-normal leading-normal">A poem by Olivia Reed</p>
                </div>
                <div
                  class="w-full bg-center bg-no-repeat aspect-video bg-cover rounded-lg flex-1"
                  style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuDuUXPx6-4XkjetBcRsCoeL6H6o_Z9upkr_As_T3uKX1hAKIjflDxqglymUzSxZIkXc9vEI83bktOVE4fdFnZ7FwTTtywUXtO0IAW6beTIGW-zuuTh6cnzWPvHUCMnV_1a64EBXAv3Xs6EeLjkvfy8lDpn8cgTWT472nhxhNBpLeQLQ01ceo8K_8WYTTCr9RW_vnKjSheNeCRFgWXM_g1dHsCy63tGpT1qvV47QNTvfJutUrYI4FtOxGxTvVsYpljpPwyRGe3Hhh3U");'
                ></div>
              </div>
            </div>
            <div class="@container">
              <div class="flex flex-col justify-end gap-6 px-4 py-10 @[480px]:gap-8 @[480px]:px-10 @[480px]:py-20">
                <div class="flex flex-col gap-2 text-center">
                  <h1
                    class="text-[#111418] tracking-light text-[32px] font-bold leading-tight @[480px]:text-4xl @[480px]:font-black @[480px]:leading-tight @[480px]:tracking-[-0.033em] max-w-[720px]"
                  >
                    Stay Updated
                  </h1>
                  <p class="text-[#111418] text-base font-normal leading-normal max-w-[720px">Get the latest articles delivered to your inbox.</p>
                </div>
                <div class="flex flex-1 justify-center">
                  <label class="flex flex-col min-w-40 h-14 max-w-[480px] flex-1 @[480px]:h-16">
                    <div class="flex w-full flex-1 items-stretch rounded-lg h-full">
                      <input
                        placeholder="Your email"
                        class="form-input flex w-full min-w-0 flex-1 resize-none overflow-hidden rounded-lg text-[#111418] focus:outline-0 focus:ring-0 border-none bg-[#f0f2f4] focus:border-none h-full placeholder:text-[#637588] px-4 rounded-r-none border-r-0 pr-2 text-sm font-normal leading-normal @[480px]:text-base @[480px]:font-normal @[480px]:leading-normal"
                        value=""
                      />
                      <div class="flex items-center justify-center rounded-r-lg border-l-0 border-none bg-[#f0f2f4] pr-2">
                        <button
                          class="flex min-w-[84px] max-w-[480px] cursor-pointer items-center justify-center overflow-hidden rounded-lg h-10 px-4 @[480px]:h-12 @[480px]:px-5 bg-[#1672ce] text-white text-sm font-bold leading-normal tracking-[0.015em] @[480px]:text-base @[480px]:font-bold @[480px]:leading-normal @[480px]:tracking-[0.015em]"
                        >
                          <span class="truncate">Subscribe</span>
                        </button>
                      </div>
                    </div>
                  </label>
                </div>
              </div>
            </div>
            <footer class="flex flex-col gap-6 px-5 py-10 text-center @container">
              <div class="flex flex-wrap items-center justify-center gap-6 @[480px]:flex-row @[480px]:justify-around">
                <a class="text-[#637588] text-base font-normal leading-normal min-w-40" href="#">About</a>
                <a class="text-[#637588] text-base font-normal leading-normal min-w-40" href="#">Contact</a>
                <a class="text-[#637588] text-base font-normal leading-normal min-w-40" href="#">Privacy Policy</a>
                <a class="text-[#637588] text-base font-normal leading-normal min-w-40" href="#">Terms of Service</a>
              </div>
              <div class="flex flex-wrap justify-center gap-4">
                <a href="#">
                  <div class="text-[#637588]" data-icon="TwitterLogo" data-size="24px" data-weight="regular">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                      <path
                        d="M247.39,68.94A8,8,0,0,0,240,64H209.57A48.66,48.66,0,0,0,168.1,40a46.91,46.91,0,0,0-33.75,13.7A47.9,47.9,0,0,0,120,88v6.09C79.74,83.47,46.81,50.72,46.46,50.37a8,8,0,0,0-13.65,4.92c-4.31,47.79,9.57,79.77,22,98.18a110.93,110.93,0,0,0,21.88,24.2c-15.23,17.53-39.21,26.74-39.47,26.84a8,8,0,0,0-3.85,11.93c.75,1.12,3.75,5.05,11.08,8.72C53.51,229.7,65.48,232,80,232c70.67,0,129.72-54.42,135.75-124.44l29.91-29.9A8,8,0,0,0,247.39,68.94Zm-45,29.41a8,8,0,0,0-2.32,5.14C196,166.58,143.28,216,80,216c-10.56,0-18-1.4-23.22-3.08,11.51-6.25,27.56-17,37.88-32.48A8,8,0,0,0,92,169.08c-.47-.27-43.91-26.34-44-96,16,13,45.25,33.17,78.67,38.79A8,8,0,0,0,136,104V88a32,32,0,0,1,9.6-22.92A30.94,30.94,0,0,1,167.9,56c12.66.16,24.49,7.88,29.44,19.21A8,8,0,0,0,204.67,80h16Z"
                      ></path>
                    </svg>
                  </div>
                </a>
                <a href="#">
                  <div class="text-[#637588]" data-icon="InstagramLogo" data-size="24px" data-weight="regular">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                      <path
                        d="M128,80a48,48,0,1,0,48,48A48.05,48.05,0,0,0,128,80Zm0,80a32,32,0,1,1,32-32A32,32,0,0,1,128,160ZM176,24H80A56.06,56.06,0,0,0,24,80v96a56.06,56.06,0,0,0,56,56h96a56.06,56.06,0,0,0,56-56V80A56.06,56.06,0,0,0,176,24Zm40,152a40,40,0,0,1-40,40H80a40,40,0,0,1-40-40V80A40,40,0,0,1,80,40h96a40,40,0,0,1,40,40ZM192,76a12,12,0,1,1-12-12A12,12,0,0,1,192,76Z"
                      ></path>
                    </svg>
                  </div>
                </a>
                <a href="#">
                  <div class="text-[#637588]" data-icon="FacebookLogo" data-size="24px" data-weight="regular">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24px" height="24px" fill="currentColor" viewBox="0 0 256 256">
                      <path
                        d="M128,24A104,104,0,1,0,232,128,104.11,104.11,0,0,0,128,24Zm8,191.63V152h24a8,8,0,0,0,0-16H136V112a16,16,0,0,1,16-16h16a8,8,0,0,0,0-16H152a32,32,0,0,0-32,32v24H96a8,8,0,0,0,0,16h24v63.63a88,88,0,1,1,16,0Z"
                      ></path>
                    </svg>
                  </div>
                </a>
              </div>
              <p class="text-[#637588] text-base font-normal leading-normal">© 2023 Inkwell. All rights reserved.</p>
            </footer>
          </div>
        </div>
      </div>
    </div>
  </body>
</html>
