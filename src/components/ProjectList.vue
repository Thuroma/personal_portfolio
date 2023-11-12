<template>
<div class="content">

    <span id="welcome">Welcome</span>

    <h2 class="title">Project Links</h2>
    <ul class="list-group list-group-flush">
        <li class="list-group-item">
            <a target="_blank" href="https://github.com/Thuroma/scout_django"><span>../Scout web app/</span></a>
        </li>
        <li class="list-group-item">
            <a target="_blank" href="https://github.com/Thuroma/scout_user_app"><span>../Scout with user accounts/</span></a>
        </li>
        <li class="list-group-item">
            <a target="_blank" href="https://www.figma.com/file/XeDgl79XSWcydnKrCxImkN/Serve-and-Save?type=design&node-id=0%3A1&mode=design&t=K4gmvDS0tj2TFbDx-1"><span>../Neighborhood volunteer app/</span></a>
        </li>
    </ul>

    <h2 class="title">Capstone Projects</h2>
    <div>
        <ul class="list-group list-group-flush">
            <li class="list-group-item">
                <a target="_blank" href="https://github.com/Thuroma/capstone_project_three_apis-dawite-matt-sophanda-thurman-zacharia"><span>../Group search project/</span></a>
            </li>
            <li class="list-group-item">
                <a target="_blank" href="https://github.com/mctc-itec/lmn-project-group-1"><span>../Group venue blog project/</span></a>
            </li>
        </ul>
    </div>

    <h2 class="title"></h2>
    <div>
        <ul class="list-group list-group-horizontal">
            <li class="list-group-item icon-link">
                <a target="_blank" href="https://github.com/Thuroma/"><img href="https://github.com/Thuroma/" src="../assets/github_icon.png" alt="">github</a>
            </li>
            <li class="list-group-item icon-link">
                <a target="_blank" href="https://www.linkedin.com/in/tthoma/"><img href="https://www.linkedin.com/in/tthoma/" src="../assets/linkedin_icon.png" alt="">LinkedIn</a>
            </li>
            <li class="list-group-item icon-link">
                <a target="_blank" href="https://www.figma.com/files/user/1228700559470689511"><img href="https://www.figma.com/files/user/1228700559470689511" src="../assets/figma_icon.png" alt="">Figma</a>
            </li>
        </ul>
    </div>
</div>

</template>

<script>

export default {
    name: 'ProjectList',
}

</script>

<style scoped>

.content {
    text-align: left;
    padding: 10px;
}

.title {
    font-family: 'Josefin Sans', sans-serif;
    font-size: 3rem;
    color: rgb(191,155,48);
}

#welcome {
    font-family: 'Josefin Sans', sans-serif;
    font-size: 6rem;
    color: rgb(191,155,48);
}

a, li {
    color: white;
    border: 2px gray;
    background-color: rgb(0, 0, 0, 0.0);
    font-family: 'Roboto', sans-serif;
    font-size: 1rem;
}

</style>