<script>
    export let name
    export let nickname
</script>

<div class="Profile">
    <div class="Profile-content">
        <div class="Profile-avatar">
            <img
                src="https://scontent.fclo1-4.fna.fbcdn.net/v/t1.6435-9/138164380_102415318497622_1258902633834582890_n.jpg?_nc_cat=107&ccb=1-5&_nc_sid=174925&_nc_ohc=dH1w6Jk4ENoAX9ZKKnI&_nc_ht=scontent.fclo1-4.fna&oh=5487163adfb258f6cf4d8ace24ed4a52&oe=61A29E8B"
                alt=""
            />
        </div>
        <div class="Profile-info">
            <h2>{nickname}</h2>
            <span>{name}</span>
        </div>
    </div>
</div>

<style>
    .Profile-content {
        display: flex;
        align-items: center;
    }
    .Profile-avatar img {
        width: 42px;
        height: 42px;
        border-radius: 50%;
    }
    .Profile-info {
        margin: 0 0 0 0.5em;
    }
    .Profile-info h2 {
        font-size: 14px;
        color: black;
        margin: 0;
        padding: 0;
    }
    .Profile-info span {
        font-size: 12px;
        font-weight: normal;
    }
</style>
