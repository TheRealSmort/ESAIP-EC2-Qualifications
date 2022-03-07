# Write-Up

We have to download a .pcapng file :

![Untitled](Write-Up%20809be/Untitled.png)

We are going to use Wireshark to open it.

![Untitled](Write-Up%20809be/Untitled%201.png)

As a reflex, the first thing I did was to check iff there is HTTP objects to export 

(File → Export Objects → HTTP...)

Neat, there are some files : 2 .jpg and a .zip

![Untitled](Write-Up%20809be/Untitled%202.png)

Let’s save them.

I opened the first image “Strong.png”

![strong.jpg](Write-Up%20809be/strong.jpg)

Nothing at plain sight

Let’s try the second one “chat_link.jpg”

![chat_link.jpg](Write-Up%20809be/chat_link.jpg)

So cute, but still nothing.

After unzip the chats.zip folder we find a lot of cats images and at the end we have the image “wake_up.png” :

![wake_up.png](Write-Up%20809be/wake_up.png)

Flag : R2Lille{w1r35h4rk_15_my_G00d_fr13nd}