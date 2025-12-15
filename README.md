# PrunePDF
Automatically detect and remove redundant incrementally built slides from PDF presentations.

## Overview
PrunePDF is a simple **Python** tool that cleans up PDF presentations by detecting and removing duplicate slides.

Teachers love exporting their incrementally built presentations as `.pdf` files without filtering. What should be **20-slide presentations** can end up as a **100-slide PDF** with **80 incremental duplicates**.

This forces students to press the `→` key a **bajillion** times while navigating through repeated content.

**Workflow**
| Stage                 | Slide Count                               |
| --------------------- | ----------------------------------------- |
| Original presentation | 20 slides                                 |
| Exported PDF          | 100 slides (`80` incremental duplicates)  |
| After PrunePDF        | 20 slides                                 |

PrunePDF fixes these incremental exports, reducing clutter and making studying just a bit less painful.
