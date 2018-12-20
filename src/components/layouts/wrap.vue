<template>
    <div class="vdw-wrapper">
        <div class="vdw-wrapper__container">
            <div class="vdw-wrapper__inner">
                <div class="vdw-wrapper__header">
                    {% include wedding/header.html %}
                </div>
                <div class="vdw-wrapper__content">
                    <!-- invite -->
                    {% include wedding/invite.html %}
                    <!-- bride -->
                    {% include wedding/bride.html %}
                    <!-- groom -->
                    {% include wedding/groom.html %}
                    <!-- venue -->
                    {% include wedding/venue.html %}
                                            
                </div>
                <!-- footer -->
                {% include wedding/footer.html %}
            </div>
        </div>
    </div>
</template>
