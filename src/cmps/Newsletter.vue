<template>
<div class="newsletter">
    <div class="email">
        <div>
            <span class="bold white size-35 email-title">Get early access today</span>
        </div> <br>
        <div>
            <span class="white">It only takes a minute to sign up and our free starter tier is extremely generous. If you have any questions, our support team would be happy to help you</span>
        </div> <br>
        <div class="inputAndButton">
            <div class="input-wrapper">
                <input placeholder="email@example.com" type="text" id="email-input">
            </div>
            <div class="button-wrapper">
                <Button>
                    Get Started For Free
                </Button>
            </div>
        </div>
    </div>  
    </div>  
</template>

<script>
import Button from '../cmps/Button';
export default {
    components: {
        Button
    }
}
</script>