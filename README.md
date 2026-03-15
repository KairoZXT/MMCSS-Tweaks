# ⚡ MMCSS Tweaks

💬 **Community & Support**

Join the Discord server for help, updates, and optimization. 

👉 [Join the Discord](https://discord.gg/2MDj4hw7qX)

# 👏 About

MMCSS Tweaks is an open-source Windows batch utility that automatically optimizes key Multimedia Class Scheduler Service (MMCSS) system profile settings for improved performance, lower latency, and better system responsiveness.

The script modifies several Windows scheduling and multimedia priority settings commonly adjusted by advanced tweakers. These settings influence how Windows allocates CPU time between foreground applications and background services 

Included tweaks focus on achieving optimal balance between performance, stability, and system responsiveness.

The script automatically configures recommended values for:

<b>Win32PrioritySeparation</b> – Controls CPU scheduling behavior between foreground and background tasks

<b>LazyModeTimeout</b> – Adjusts how long MMCSS waits before switching scheduling behavior

<b>NetworkThrottlingIndex</b> – Removes unnecessary network throttling used for multimedia streaming

<b>MMCSS System Profile settings</b> – Improves task scheduling priority for latency-sensitive workloads

Inside the batch file you will also find clear explanations for every tweak, including:

What the setting does

Why it impacts performance

The recommended value used by the script

This makes the tool useful both for optimization and learning how Windows scheduling works.

# 🚨 Disclaimer

This script modifies Windows registry settings related to system scheduling

While the tweaks given do benefit my system, some systems vary and results may differ depending on hardware, drivers, and Windows version.

The author is not responsible for any damage, instability or data loss that may occur from running this script.

Use at your own risk.

# 💻 Requirements

Windows 10 or Windows 11

Administrator privileges

Basic understanding of Windows optimization (recommended)

❓ How to Use

Go to the Releases section of this repository

Download the batch file

Right-click the file and select Run as Administrator

The script will automatically apply the optimized MMCSS settings

After applying the tweaks, restart your computer for the changes to fully take effect.

# 🔧 What This Script Tweaks
<b>Win32PrioritySeparation</b>

Adjusts how Windows distributes CPU time between foreground applications and background services.

Optimized values prioritize active applications while maintaining stable background scheduling.

<b>LazyModeTimeout</b>

Controls how long MMCSS remains in certain scheduling states before switching behavior.

Proper tuning can reduce scheduling delays and improve responsiveness.

<b>NetworkThrottlingIndex</b>

Windows applies network throttling to prevent multimedia tasks from overwhelming the system.

This script disables unnecessary throttling to reduce network latency and improve throughput.

# 📜 License

This project is released under the MIT License.

You are free to use, modify, and distribute this script as long as the original license is included.
