# Evenesy

**Eveη simple. Even easλ.**  

Get ready for something **revolutionary**. Our beta drops on **12/11**.  

## Countdown to Beta

<div id="countdown" style="font-size: 24px; font-weight: bold;"></div>

<script>
const countdownElement = document.getElementById("countdown");
const targetDate = new Date("2025-11-12T00:00:00"); // Beta release date

function updateCountdown() {
    const now = new Date();
    const diff = targetDate - now;

    if (diff <= 0) {
        countdownElement.innerHTML = "🚀 Beta is live!";
        clearInterval(interval);
        return;
    }

    const days = Math.floor(diff / (1000 * 60 * 60 * 24));
    const hours = Math.floor((diff / (1000 * 60 * 60)) % 24);
    const minutes = Math.floor((diff / (1000 * 60)) % 60);
    const seconds = Math.floor((diff / 1000) % 60);

    countdownElement.innerHTML = 
        `${days}d ${hours}h ${minutes}m ${seconds}s`;
}

const interval = setInterval(updateCountdown, 1000);
updateCountdown();
</script>

---

Stay tuned. Something **Evenesy** is coming.
