---
layout: post
title: "My First Post"
date: 2025-07-13
---

This is my first post on my new blog inspired by worthdoingbadly.com. 

Here’s a code sample from developer.auth0.com.

<pre class="sc-5bf67fa3-7 eMPNsL" style="tab-size: 2; hyphens: none; white-space: pre-wrap; overflow-wrap: normal; font-family: Menlo, Monaco, &quot;Courier New&quot;, monospace; font-size: 14px; color: rgb(118, 217, 230); text-shadow: none; background: rgb(42, 42, 42); padding: 15px; border-radius: 4px; border: 1px solid rgb(225, 225, 232); overflow: auto; position: relative;"><code class="language-javascript" style="white-space: pre-wrap; tab-size: 2; hyphens: none; overflow-wrap: normal; font-family: Menlo, Monaco, &quot;Courier New&quot;, monospace; font-size: 14px; color: rgb(118, 217, 230); text-shadow: none;"><span class="token" style="color: rgb(239, 59, 125);">const</span><span> </span><span class="token function-variable function">login</span><span> </span><span class="token" style="color: rgb(167, 122, 254);">=</span><span> </span><span class="token" style="color: rgb(239, 59, 125);">async</span><span> </span><span class="token" style="color: rgb(190, 190, 197);">(</span><span class="token" style="color: rgb(190, 190, 197);">)</span><span> </span><span class="token" style="color: rgb(167, 122, 254);">=&gt;</span><span> </span><span class="token" style="color: rgb(190, 190, 197);">{</span><span>
</span><span>  </span><span class="token" style="color: rgb(239, 59, 125);">await</span><span> auth0</span><span class="token" style="color: rgb(190, 190, 197);">.</span><span class="token function">loginWithRedirect</span><span class="token" style="color: rgb(190, 190, 197);">(</span><span class="token" style="color: rgb(190, 190, 197);">{</span><span>
</span><span>    </span><span class="token literal-property property">redirect_uri</span><span class="token" style="color: rgb(167, 122, 254);">:</span><span> window</span><span class="token" style="color: rgb(190, 190, 197);">.</span><span>location</span><span class="token" style="color: rgb(190, 190, 197);">.</span><span>origin
</span><span>  </span><span class="token" style="color: rgb(190, 190, 197);">}</span><span class="token" style="color: rgb(190, 190, 197);">)</span><span class="token" style="color: rgb(190, 190, 197);">;</span><span>
</span><span></span><span class="token" style="color: rgb(190, 190, 197);">}</span><span class="token" style="color: rgb(190, 190, 197);">;</span></code></pre>