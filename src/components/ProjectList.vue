<template>

    <div class="card">

        <div class="card-body">
            <h2>Projects</h2>
            <ul>
                <li>
                    <a target="_blank" href="https://github.com/Thuroma/scout_django"><span>Scout web app</span></a>
                </li>
                <li>
                    <a target="_blank" href="https://github.com/Thuroma/scout_user_app"><span>Scout with user accounts</span></a>
                </li>
                <li>
                    <a target="_blank" href="https://www.figma.com/file/XeDgl79XSWcydnKrCxImkN/Serve-and-Save?type=design&node-id=0%3A1&mode=design&t=K4gmvDS0tj2TFbDx-1"><span>Neighborhood volunteer app</span></a>
                </li>
            </ul>

            <h2>Capstone Projects</h2>
            <div>
                <ul>
                    <li>
                        <a target="_blank" href="https://github.com/Thuroma/capstone_project_three_apis-dawite-matt-sophanda-thurman-zacharia"><span>Group search project</span></a>
                    </li>
                    <li>
                        <a target="_blank" href="https://github.com/mctc-itec/lmn-project-group-1"><span>Group venue blog project</span></a>
                    </li>
                </ul>
            </div>
            
            <a target="_blank" href="https://github.com/Thuroma"><span>github</span></a>
        </div>

    </div>

</template>

<script>
export default {
    name: 'ProjectList',
}

</script>

<style scoped>

.card {
    width: 300px;
    border-radius: 10px;
    box-shadow: 0 15px 25px rgba(129, 124, 124, 0.2); 
    backdrop-filter: blur(14px);
    background-color: rgba(255, 255, 255, 0.2); 
    padding: 10px;
    text-align: left;
    color: white;
}

a {
    color: white;
}

</style>