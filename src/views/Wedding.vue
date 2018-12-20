<template>
    <div class="vdw-wrapper">
        <div class="vdw-wrapper__container">
            <div class="vdw-wrapper__inner">
                <div class="vdw-wrapper__header">
                    <wedHeader/>
                </div>
                <div class="vdw-wrapper__content">                    
                    <wedInvite/>
                    <wedBride/>
                    <wedGroom/>
                    <wedVenue/>                                            
                </div>
                <!-- footer -->
                <wedFooter/>                
            </div>
        </div>
    </div>    
</template>
<script>

import wedHeader from "@/components/includes/wedding/Header";
import wedInvite from "@/components/includes/wedding/Invite";
import wedBride from "@/components/includes/wedding/Bride";
import wedGroom from "@/components/includes/wedding/Groom";
import wedVenue from "@/components/includes/wedding/Venue";

export default {
    name: "Wedding",
    components: {
        wedHeader,
        wedInvite,
        wedBride,
        wedGroom,
        wedVenue
    }
}
</script>
