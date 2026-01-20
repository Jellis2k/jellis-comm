<script lang="ts">
    let twitter = "https://x.com/Jellismk2";
    let pixiv = "https://www.pixiv.net/en/users/108093889";
    let kofi = "https://ko-fi.com/jellis";
    let maro = "https://marshmallow-qa.com/xxws6dpj26vgfdn";
    let vgen = "https://vgen.co/Jellis";
    // let jellis2k = "https://x.com/search?q=%23jellis2k&src=hashtag_click&f=live";
    let pfp = "/favicon.png";

    // let clipboard = "Jellis' Socials:\n" +
    // "Twitter/X: " + twitter + "\n" +
    // "Pixiv: " + pixiv + "\n" +
    // "Ko-fi: " + kofi + "\n" +
    // "Marshmallow-QA: " + maro;

    // function copyToClipboard() {
    //     navigator.clipboard.writeText(clipboard);
    //     alert("Copied");
    // }
</script>

<div class="min-h-screen flex flex-col items-center justify-center">
        <!-- Profile Picture here -->
    <img src={pfp} alt='jellis-pfp' class="object-center w-40 h-40 rounded-full mx-auto"/>

    <!-- Title -->
    <h1 class="text-center font-bold text-4xl p-4 m-1">
        <!-- Jellis' <span class="cursor-pointer hover:underline" on:click={copyToClipboard}>Socials</span> -->
        Jellis Socials
    </h1>

    <!-- H-Line -->
    <!-- <hr class="text-center h-1 bg-[#332e38] rounded-full border-0 w-96 mx-auto" /> -->

    <div class="flex items-center justify-center">
        <div class="flex flex-col w-96 my-3">
            <a href={twitter} target="_blank" class="text-xl p-4 m-2 rounded-xl bg-dark flex items-center transition-colors duration-50 hover:bg-[#e6d5d3] hover:text-[#332e38]">
                X / Twitter
                <img src={`https://www.google.com/s2/favicons?domain=${new URL(twitter).hostname}&sz=32`} alt="X/Twitter Icon" class="ml-auto w-5 h-5"/>
            </a>
            <a href={pixiv} target="_blank" class="text-xl p-4 m-2 rounded-xl bg-dark flex items-center transition-colors duration-50 hover:bg-[#e6d5d3] hover:text-[#332e38]">
                Pixiv
                <img src={`https://www.google.com/s2/favicons?domain=${new URL(pixiv).hostname}&sz=32`} alt="Pixiv Icon" class="ml-auto w-5 h-5"/>
            </a>
            <a href={kofi} target="_blank" class="text-xl p-4 m-2 rounded-xl bg-dark flex items-center transition-colors duration-50 hover:bg-[#e6d5d3] hover:text-[#332e38]">
                Ko-fi
                <img src={`https://www.google.com/s2/favicons?domain=${new URL(kofi).hostname}&sz=32`} alt="Pixiv Icon" class="ml-auto w-5 h-5"/>
            </a>
            <a href={maro} target="_blank" class="text-xl p-4 m-2 rounded-xl bg-dark flex items-center transition-colors duration-50 hover:bg-[#e6d5d3] hover:text-[#332e38]">
                Marshmallow
                <img src={`https://www.google.com/s2/favicons?domain=${new URL(maro).hostname}&sz=32`} alt="Pixiv Icon" class="ml-auto w-5 h-5"/>
            </a>
            <a href={vgen} target="_blank" class="text-xl p-4 m-2 rounded-xl bg-dark flex items-center transition-colors duration-50 hover:bg-[#e6d5d3] hover:text-[#332e38]">
                VGen (Closed)
                <img src={`https://www.google.com/s2/favicons?domain=${new URL(vgen).hostname}&sz=32`} alt="VGen Icon" class="ml-auto w-5 h-5"/>
            </a>
        </div>
    </div>


    <p class="text-center w-96">
        If you use my artwork online <em>(e.g., YouTube, X)</em>, <strong>please</strong> consult/credit me. 
        <br/><br/>
        <strong>Email</strong>: <u>jellis.contact@gmail.com</u>
        <!-- Monthly art & doodles → 
        <a href={jellis2k} target="_blank" class="font-bold">
            #jellis2k
        </a> -->
    </p>
</div>