<template>
<div class="home">
    <content>
        <layout row wrap>
            <flex>
                <firstsize />
                <secondsize />
                <thirdsize />
            </flex>
        </layout>
    </content>
</div>
</template>

<script>
import firstsize from "@/components/homepage/firstsize";
import secondsize from "@/components/homepage/secondsize"
import thirdsize from "@/components/homepage/thirdsize"

export default {
    components: {
        firstsize,
        secondsize,
        thirdsize
    }
};
</script>
