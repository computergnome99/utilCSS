# UtilCSS

A modern CSS framework for the UtilGroup family of Products.

Author: Calvin Bonner @computergnome99

Version: 0.0.1 (Pre-Release)

License: MIT

---

## Shadows

| Class | Mixin | Properties |
|-------|-------|------------|
| shadow-#{name} | box-shadow, text-shadow | [ xl, lg, md, sm, xs ] |
| shadow-#{name}-#{color} | box-shadow, text-shadow | [ xl, lg, md, sm, xs ], color |
| shadow-#{color} | box-shadow, text-shadow | color |

## Font
| Class | Mixin | Properties |
|-------|-------|------------|
| font-family-#{name}, ff-#{name} | font-family | [ normal / regular / text, header / display, small, serif, mono ] |
| font-size-#{name}, fs-#{name} | font-size | [ 1 - 10 ] |
| font-weight-#{name}, fw-#{name} | font-weight | [ light, ligher, normal / regular, bold, bolder, 1 - 10 ] |
| line-height-#{name}, lh-#{name} | line-height | [ 1 - 10 ] |

## Color

| Class | Mixin | Properties |
|-------|-------|------------|
| background-#{name}, bg-#{name} | background | color |
| text-#{name}, fc-#{name} | text | color |
| border-#{name}, bc-#{name} | border | color |

## Default Theme Colors
<div style="display:flex;gap:12px;flex-wrap:wrap;">
    <div style="display:flex;align-items:center;margin-bottom:8px;">
        <div style="width:16px;height:16px;border-radius:8px;background:#814EFA;border:1px solid white;"></div>
        <p style="margin:0;padding-left:8px;">Primary</p>
    </div>
    <div style="display:flex;align-items:center;margin-bottom:8px;">
        <div style="width:16px;height:16px;border-radius:8px;background:#3D62F9;border:1px solid white;"></div>
        <p style="margin:0;padding-left:8px;">Secondary</p>
    </div>
    <div style="display:flex;align-items:center;margin-bottom:8px;">
        <div style="width:16px;height:16px;border-radius:8px;background:#49B3F5;border:1px solid white;"></div>
        <p style="margin:0;padding-left:8px;">Tertiary</p>
    </div>
    <div style="display:flex;align-items:center;margin-bottom:8px;">
        <div style="width:16px;height:16px;border-radius:8px;background:#4CF46E;border:1px solid white;"></div>
        <p style="margin:0;padding-left:8px;">Success</p>
    </div>
    <div style="display:flex;align-items:center;margin-bottom:8px;">
        <div style="width:16px;height:16px;border-radius:8px;background:#F43B3B;border:1px solid white;"></div>
        <p style="margin:0;padding-left:8px;">Danger</p>
    </div>
    <div style="display:flex;align-items:center;margin-bottom:8px;">
        <div style="width:16px;height:16px;border-radius:8px;background:#E4C132;border:1px solid white;"></div>
        <p style="margin:0;padding-left:8px;">Warning</p>
    </div>
    <div style="display:flex;align-items:center;margin-bottom:8px;">
        <div style="width:16px;height:16px;border-radius:8px;background:#94B6C2;border:1px solid white;"></div>
        <p style="margin:0;padding-left:8px;">Neutral</p>
    </div>
    <div style="display:flex;align-items:center;margin-bottom:8px;">
        <div style="width:16px;height:16px;border-radius:8px;background:#E9F3FF;border:1px solid white;"></div>
        <p style="margin:0;padding-left:8px;">Light</p>
    </div>
    <div style="display:flex;align-items:center;margin-bottom:8px;">
        <div style="width:16px;height:16px;border-radius:8px;background:#0D1117;border:1px solid white;"></div>
        <p style="margin:0;padding-left:8px;">Dark</p>
    </div>
    <div style="display:flex;align-items:center;margin-bottom:8px;">
        <div style="width:16px;height:16px;border-radius:8px;background:#FFFFFF;border:1px solid white;"></div>
        <p style="margin:0;padding-left:8px;">White</p>
    </div>
    <div style="display:flex;align-items:center;margin-bottom:8px;">
        <div style="width:16px;height:16px;border-radius:8px;background:#000000;border:1px solid white;"></div>
        <p style="margin:0;padding-left:8px;">Black</p>
    </div>
</div>