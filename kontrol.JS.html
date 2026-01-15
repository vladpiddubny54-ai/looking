function showPreview(files) {
    Array.from(files).forEach(file => {
        const reader = new FileReader();

        reader.onload = () => {
            const card = document.createElement("div");
            card.className = "card";

            if (file.type.startsWith("image")) {
                const img = document.createElement("img");
                img.src = reader.result;
                card.appendChild(img);
            } else {
                const video = document.createElement("video");
                video.src = reader.result;
                video.controls = true;
                card.appendChild(video);
            }

            const upload = document.createElement("button");
            upload.textContent = "Завантажити";
            upload.className = "upload-btn";
            upload.onclick = () => {
                data.push({ name: file.name, type: file.type, src: reader.result });
                localStorage.setItem("media", JSON.stringify(data));
                draw();
                card.remove();
            };

            const cancel = document.createElement("button");
            cancel.textContent = "Скасувати";
            cancel.className = "delete-btn";
            cancel.onclick = () => card.remove();

            card.appendChild(upload);
            card.appendChild(cancel);
            previewArea.appendChild(card);
        };

        reader.readAsDataURL(file);
    });
}
