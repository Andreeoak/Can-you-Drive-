

# 🚗 Can You Drive? 

> A minimal interactive app built with Vue 3 Composition API that tells you whether you can drive based on your age.

---

## 🧪 Live Demo

👉 Enter your age and see if you're legally allowed to drive.
The answer updates reactively and is styled in green (`Yes`) or red (`No`).

---

## 🧠 Features

* ✅ **Vue 3.4** with Composition API
* 🔁 **Reactive variables** using `ref`
* ⚙️ **Computed property** (`canDrive`) with auto-updates
* 🎨 Simple CSS styling (`can`, `cannot`)
* 🧼 Normalize.css for baseline CSS reset
* ⏱ `setTimeout` updates greeting after 5 seconds

---

## 💡 How It Works

```js
const age = ref(null);

const canDrive = computed(() => {
  return age.value >= 18 ? 'Yes' : 'No';
});
```

The input field is bound to `age` via `v-model`, and `canDrive` updates automatically using Vue’s reactivity.

---

## 🖼️ Video

> Exemple of use:


https://github.com/user-attachments/assets/e560dfaf-e12c-4750-b492-9fecddee5710



---

## 🛠️ How to Run

Just save the code in an `.html` file and open it in your browser — no build tools needed!
Tip: try the Live Serve extension on VsCode for the best experience!

---

## 🚀 Next Steps

* Add form validation for non-numeric input
* Extract the component into a `.vue` file
* Add more computed logic (e.g., voting eligibility, drinking age)
* Deploy on [GitHub Pages](f) or [Netlify](f)


