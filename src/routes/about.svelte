<div class="la-about">
    <div class="aboutme">
        <img src="/mom-resize2_orig.jpg" alt=""/>
        <div class="content">
            <h2>Lisa-Anne Wooldridge</h2>
            <p>Lisa-Anne Wooldridge is an author and speaker who resides in the San Francisco Bay Area with her husband and three children. She is a serial contributor to anthologies, a former newspaper columnist, and is perpetually at work on a new novel. She is inspired by stained glass windows, illuminated manuscripts, and living where "the mountains meet the redwoods and the redwoods meet the sea." ​</p>
        </div>
    </div>
</div>
<style lang="scss">
.la-about{
    .aboutme{
        background-color: #aafff7;
        padding: 16px;
        display: flex;
        img {
            border-radius: 16px;
            box-shadow: 4px 4px 4px;
        }
        .content {
            padding: 32px;
        }
    }
}
@media only screen and (max-width: 600px) {
    .la-about{
        .aboutme{
            flex-direction: column;
        }
    }

}

</style>