<script>
  import icon from '../../images/icon/ihg.png';
</script>

<div class="flex justify-between items-center bg-[#0c0c1c] py-4 px-8" id="navbar-container">
  <!-- Logo -->
  <div class="ml-12" id="icon-container">
    <img src={icon} alt="Logo" class="w-16 hover:scale-110 transition-transform duration-500" />
  </div>

  <!-- Navigation Links -->
  <div class="flex space-x-16" id="pages-container">
    <a href="/" class="nav-item group">
      <div class="nav-content bg-gradient-to-tr from-[#2443a1] to-[#5eb3f4] group-hover:shadow-[0_6px_20px_3px_rgba(30,100,255,0.7)] transition-all duration-500">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 24 24"
          width="20"
          height="20"
          class="fill-current icon group-hover:rotate-12 text-[#bee3ff] group-hover:text-white transition-all duration-500"
        >
          <path
            d="M23.121,9.069,15.536,1.483a5.008,5.008,0,0,0-7.072,0L.879,9.069A2.978,2.978,0,0,0,0,11.19v9.817a3,3,0,0,0,3,3H21a3,3,0,0,0,3-3V11.19A2.978,2.978,0,0,0,23.121,9.069ZM15,22.007H9V18.073a3,3,0,0,1,6,0Zm7-1a1,1,0,0,1-1,1H17V18.073a5,5,0,0,0-10,0v3.934H3a1,1,0,0,1-1-1V11.19a1.008,1.008,0,0,1,.293-.707L9.878,2.9a3.008,3.008,0,0,1,4.244,0l7.585,7.586A1.008,1.008,0,0,1,22,11.19Z"
          />
        </svg>
        <span class="text-[#bee3ff] font-bold group-hover:text-white transition-all duration-500">Accueil</span>
      </div>
    </a>

    <a href="/jeux" class="nav-item group">
      <div class="nav-content bg-gradient-to-tr from-[#2c6054] to-[#79f8dd] group-hover:shadow-[0_6px_20px_3px_rgba(62,158,136,0.7)] transition-all duration-500">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 512 512"
          width="20"
          height="20"
          class="fill-current icon group-hover:rotate-12 text-[#d4fff6] group-hover:text-white transition-all duration-500"
        >
        <path d="M473.759,107.286c-19.12-31.867-53.112-53.112-91.353-53.112H127.469c-38.241,0-72.232,21.245-91.353,53.112  C12.747,149.776,0,196.515,0,245.378c0,116.846,46.739,212.448,106.224,212.448c31.867,0,57.361-29.743,76.481-91.353  c2.124-8.498,10.622-14.871,21.245-14.871h104.1c8.498,0,16.996,6.373,21.245,14.871c19.12,61.61,44.614,91.353,76.481,91.353  c59.485,0,106.224-95.602,106.224-212.448C509.876,196.515,497.129,149.776,473.759,107.286z M403.651,415.336  c-6.373,0-21.245-16.996-36.116-61.61c-8.498-27.618-33.992-44.614-61.61-44.614H203.95c-27.618,0-53.112,19.12-61.61,44.614  c-14.871,44.614-29.743,61.61-36.116,61.61c-21.245,0-63.734-65.859-63.734-169.958c0-40.365,10.622-80.73,29.743-116.846  c12.747-19.12,33.992-31.867,55.237-31.867h254.938c21.245,0,42.49,12.747,55.237,31.867c19.12,36.116,29.743,76.481,29.743,116.846  C467.386,349.477,424.896,415.336,403.651,415.336z"/>
        <path d="M192,192h-21.333v-21.333c0-12.8-8.533-21.333-21.333-21.333c-12.8,0-21.333,8.533-21.333,21.333V192h-21.333  c-12.8,0-21.333,8.533-21.333,21.333c0,12.8,8.533,21.333,21.333,21.333H128V256c0,12.8,8.533,21.333,21.333,21.333  c12.8,0,21.333-8.533,21.333-21.333v-21.333H192c12.8,0,21.333-8.533,21.333-21.333C213.333,200.533,204.8,192,192,192z"/>
        <circle cx="394.667" cy="181.333" r="32" />
        <circle cx="330.667" cy="245.333" r="32" />
        </svg>
        <span class="text-[#d4fff6] font-bold group-hover:text-white transition-all duration-500">Jeux</span>
      </div>
    </a>

    <a href="/prochainement" class="nav-item group">
      <div class="nav-content bg-gradient-to-tr from-[#4e1cc2] to-[#ca82f7] group-hover:shadow-[0_6px_20px_3px_rgba(105,70,212,0.7)] transition-all duration-500">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 24 24"
          width="20"
          height="20"
          class="fill-current icon group-hover:rotate-12 text-[#e0d3ff] group-hover:text-white transition-all duration-500"
        >
        <path d="M1.879,17.878a11.259,11.259,0,0,0-1.835,4,1.739,1.739,0,0,0,2.083,2.082,11.263,11.263,0,0,0,3.994-1.834h0A3,3,0,0,0,1.879,17.878Zm2.828,2.829h0a10.07,10.07,0,0,1-2.6,1.184,10.1,10.1,0,0,1,1.184-2.6,1,1,0,0,1,1.414,1.414ZM18,8.5a2.5,2.5,0,0,1-5,0A2.5,2.5,0,0,1,18,8.5ZM20.972,0h0A15.487,15.487,0,0,0,8.634,6.006,11.065,11.065,0,0,0,4.065,7.169,8.1,8.1,0,0,0,.243,10.835a2.955,2.955,0,0,0,.25,2.8A3.009,3.009,0,0,0,3.014,15H5.5A3.517,3.517,0,0,1,9,18.5v2.486a3.009,3.009,0,0,0,1.363,2.521,2.955,2.955,0,0,0,2.8.25,8.1,8.1,0,0,0,3.666-3.822,11.065,11.065,0,0,0,1.163-4.569A15.507,15.507,0,0,0,24,3,3.009,3.009,0,0,0,20.972,0ZM4.346,13H3.014a1,1,0,0,1-.85-.461.95.95,0,0,1-.085-.91A6.176,6.176,0,0,1,4.962,8.957a8.993,8.993,0,0,1,1.993-.72A34.361,34.361,0,0,0,4.346,13Zm10.7,6.038a6.18,6.18,0,0,1-2.671,2.883.951.951,0,0,1-.911-.085,1,1,0,0,1-.461-.85V19.654a34.361,34.361,0,0,0,4.763-2.609A8.993,8.993,0,0,1,15.043,19.038Zm.135-4.02a29.92,29.92,0,0,1-4.271,2.471,5.5,5.5,0,0,0-4.4-4.4A29.92,29.92,0,0,1,8.982,8.822C12.35,4.124,15.84,2.147,21,2a1,1,0,0,1,1,.972C21.853,8.16,19.876,11.65,15.178,15.018Z" />
        </svg>
        <span class="text-[#e0d3ff] font-bold group-hover:text-white transition-all duration-500">Prochainement</span>
      </div>
    </a>
  </div>

  <!-- Right Section -->
  <div id="right-container" class="flex space-x-5 mr-12">
    <!-- Settings Icon -->
    <div id="settings-container" class="hover:scale-110 transition-transform duration-500">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 24 24"
        width="24"
        height="24"
        class="fill-current text-gray-400 hover:text-white"
      >
      <path d="M1,4.75H3.736a3.728,3.728,0,0,0,7.195,0H23a1,1,0,0,0,0-2H10.931a3.728,3.728,0,0,0-7.195,0H1a1,1,0,0,0,0,2ZM7.333,2a1.75,1.75,0,1,1-1.75,1.75A1.752,1.752,0,0,1,7.333,2Z"/>
      <path d="M23,11H20.264a3.727,3.727,0,0,0-7.194,0H1a1,1,0,0,0,0,2H13.07a3.727,3.727,0,0,0,7.194,0H23a1,1,0,0,0,0-2Zm-6.333,2.75A1.75,1.75,0,1,1,18.417,12,1.752,1.752,0,0,1,16.667,13.75Z"/>
      <path d="M23,19.25H10.931a3.728,3.728,0,0,0-7.195,0H1a1,1,0,0,0,0,2H3.736a3.728,3.728,0,0,0,7.195,0H23a1,1,0,0,0,0-2ZM7.333,22a1.75,1.75,0,1,1,1.75-1.75A1.753,1.753,0,0,1,7.333,22Z" />
      </svg>
    </div>

    <!-- Profile Icon -->
    <div id="profile-container" class="hover:scale-110 transition-transform duration-500">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 24 24"
        width="24"
        height="24"
        class="fill-current text-gray-400 hover:text-white"
      >
        <path d="m12,0C5.383,0,0,5.383,0,12s5.383,12,12,12,12-5.383,12-12S18.617,0,12,0Zm-4,21.164v-.164c0-2.206,1.794-4,4-4s4,1.794,4,4v.164c-1.226.537-2.578.836-4,.836s-2.774-.299-4-.836Zm9.925-1.113c-.456-2.859-2.939-5.051-5.925-5.051s-5.468,2.192-5.925,5.051c-2.47-1.823-4.075-4.753-4.075-8.051C2,6.486,6.486,2,12,2s10,4.486,10,10c0,3.298-1.605,6.228-4.075,8.051Zm-5.925-15.051c-2.206,0-4,1.794-4,4s1.794,4,4,4,4-1.794,4-4-1.794-4-4-4Zm0,6c-1.103,0-2-.897-2-2s.897-2,2-2,2,.897,2,2-.897,2-2,2Z" />
      </svg>
    </div>
  </div>
</div>

<style>
  .nav-item {
    display: flex;
    align-items: center;
    text-decoration: none;
  }

  .nav-content {
    display: flex;
    align-items: center;
    padding: 0.5rem 1rem;
    border-radius: 9999px;
    transition: all 0.3s ease-in-out;
  }

  .icon {
    margin-right: 0.5rem;
    transition: transform 0.5s ease-in-out;
  }

  .nav-content:hover {
    transform: translateY(-2px);
  }
</style>