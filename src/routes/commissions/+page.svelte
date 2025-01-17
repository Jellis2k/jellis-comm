<script lang="ts">
    let status = "CLOSED";
</script>

<div class="min-h-screen flex flex-col items-center sm:w-7/12 w-11/12 sm:mx-auto mx-8">
    <h1 class="text-4xl font-bold mt-36">Commission Info</h1>
    <a class="" href="#contact">[Skip to Contact Info]</a>

    <h2 class="text-3xl mt-8"> Status: 
        <strong class="{status === 'CLOSED' ? 'text-red-500' : 'text-green-500'}">{status}</strong>
    </h2>

    <hr class="border-t-8 border-[#332e38] w-full mt-8 mb-8" />

    <!-- TOS -->
    <h2 class="text-3xl">TERMS OF SERVICE: (WIP)</h2>
    <ul class="list-disc text-lg">
        <li>Payment is only in USD. No refunds can be issused.</li>
        <li>All commissions are for personal use only. You may not profit from or use the commissioned artwork commercially unless explicitly discussed and agreed upon beforehand.</li>
        <li>Commissions are not handled first-come, first-served basis. I will choose the project to work on after reviewing all submitted requests.</li>
        <li>If you share or use the artwork anywhere, ensure credit to me as the artist is visible (e.g., "Art by @Jellis2k", ambiguous: "Jellis").</li>
        <li>Please refrain from asking me to mimic another artist's style.</li>
        <li>I can only work create simple backgrounds; refer to my previous works as reference.</li>
        <li>Once payment is made and a draft/sketch is approved, the process may take 1-3 weeks to complete (maximum) however, this duration may vary based on the complexity of your request.</li>
        <li>Small revisions are allowed during the sketch phase for free. Complex revisions require a small fee.</li>
        <li>Absolutely DO NOT use my artwork to train any AI models.</li>
        <li class="mt-4"><strong>By submitting a request you confirm that you have read and agree to the Terms and Service above.</strong></li>
    </ul>

    <div class="flex space-x-8 mt-8">
        <!-- Will Do -->
        <div class="flex flex-col w-1/2">
            <h2 class="text-3xl">Will Do:</h2>
            <ul class="text-lg">
                <li>Anime Girls!!! Character Fanart, Kemonomimi, Food, Slightly Suggestive</li>
            </ul>
        </div>

        <!-- Won't Do -->
        <div class="flex flex-col w-1/2">
            <h2 class="text-3xl">Won't Do:</h2>
            <ul class="text-lg">
                <li>Create & Design an OC/Vtuber, Furries/Scalies, R-18 (and themes), Hateful Imagery, Mechas, Vehicles/Machinery, Armor, Firearms</li>
            </ul>
        </div>
    </div>

    <h2 class="text-3xl mt-8" id="process">PROCESS</h2>
    <ul class="list-disc text-lg">
        <li>Submit your request via message/email.</li>
        <li>Discuss any details/questions and finalize terms.</li>
        <li>Pay 50% upfront to begin work.</li>
        <li>Sketch piece is provided for review. Progress updates available on request. </li>
        <li>Once artwork is completed I'll ask for the remaining 50% of payment.</li>
        <li>Receive the final file. I may upload it to X/Twitter unless requested not to beforehand.</li>
    </ul>

    <hr class="border-t-8 border-[#332e38] w-full mt-8 mb-8" />

    <h2 class="text-3xl">COMMISSION TYPES: (WIP)</h2>
    <ul class="text-lg">
        <li>This isn't final yet. I'm just adding these for space.</li>
        <li>Background is $10-$30 depending on complexity</li>
    </ul>
    
    <!-- Bust up -->
    <h3 class="text-2xl text-center mt-4">Bust Up: $69</h3>
    <img src="https://pbs.twimg.com/media/GgQTLVHXMAANF75?format=jpg" 
        alt="Raki New Years in Kimono" class="w-10/12 h-auto p-2"/>
    <img src="https://pbs.twimg.com/media/GcJjIL_WwAAB2ee?format=jpg" 
        alt="Raki's Pocky Day (Shoujo)" class="w-6/12 h-auto p-2"/>


    <!-- Full body -->
    <h3 class="text-2xl text-center mt-4">Full Body: $420</h3>
    <div class="flex justify-between w-full">
        <img 
            src="https://pbs.twimg.com/media/GdxKjJJXIAATqGr?format=jpg" 
            alt="M0MORI Debut Art" 
            class="w-1/2 p-2"
        />
        <img 
            src="https://pbs.twimg.com/media/GePtI60XQAAsAUl?format=jpg" 
            alt="Ayu 2.0 Debut Art" 
            class="w-1/2 p-2"
        />
    </div>

    <hr class="border-t-8 border-[#332e38] w-full mt-8 mb-8" />

    <div class="text-center">
        <p class="text-2xl">10% off</p>
        <p class="text-2xl">If commissioned to draw one of my oshis</p>
        <p>(This isn't a joke and I'm not saying who they are.)</p>
    </div>
    

    <hr class="border-t-8 border-[#332e38] w-full mt-8 mb-8" />

    <!-- Request Form -->
    <div>
        <h2 class="text-3xl text-center">REQUEST FORM</h2>
        <p class="mb-4">A general guideline of what to provide when requesting:</p>
        <ul class="text-lg mb-4">
            <li><strong>About You:</strong> Your username or X/Twitter handle.</li>
            <li><strong>Commission Type:</strong> Negotiable</li>
            <li><strong>Character Details:</strong> Name, image references.</li>
            <li><strong>(optional) Additional Details:</strong> Outfit references, pose references, facial expressions, other (these help a lot).</li>
        </ul>
    </div>

    <hr class="border-t-8 border-[#332e38] w-full mt-8 mb-8" />

    <!-- Contact -->
    <div class="text-center my-16">
        <h2 class="text-3xl" id="contact">CONTACT INFO</h2>
        <h3 class="text-xl my-2">
            <strong class="text-[#fc6e83;]">X / Twitter: </strong>
            <a href="https://x.com/Jellis2k" class="underline">@Jellis2k</a>
        </h3>

        <h3 class="text-xl my-2">
            <strong class="text-[#fc6e83;]">Email: </strong>
            <a href="https://x.com/Jellis2k" class="">jellisvt.official@gmail.com</a>
        </h3>
        <p class="my-6">Don't hesitate to contact through (preferably) X/Twitter DMs, or Email for questions. Clear communication helps!</p>
    </div>

</div> 
<!-- End of content -->
 
<style>
    h1, h2 {
        color: #fc6e83;
    }
</style>