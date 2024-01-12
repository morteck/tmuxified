# Configuration dot file for customized tmux.

## This repository houses my personally created tmux configs. Tmux, meaning "terminal multiplexer", is based on a similar terminal multiplexer called "screen." The idea behind both tmux and screen is to enable a user to run multiple terminal sessions within a single terminal window or SSH session. This allows you, the user/admin, to create and manage multiple terminal sessions, detach and reattach to sessions, and run commands concurrently. ## 

## Key Features: 

- **Intuitive Key Bindings:** Simplified and easy-to-remember key bindings for common tmux actions.
- **Custom Status Bar:** A clean and informative status bar at the bottom to keep you informed about your sessions, windows, and panes.
- **Plugin Support:** Easily extend functionality with popular tmux plugins for a tailored experience.

## Get Started: ##

1. **Clone the Repository:** 
    
- `git clone https://github.com/morteck/tmuxified.git`
    
- **Copy .tmux.config to Your Home Directory:**
        
- `cp <repo-location>/.tmux.config ~/.tmux.config`
    
- **Reload tmux Configuration:**
    
1. `tmux source-file ~/.tmux.config`
    
There's need to restart your tmux session as there is already a line within the dot file to automate this step. Alternatively, you may comment out the line and perform a manual restart if needed. 

## Key Features

- **Custom Status Bar:** A clean and informative status bar at the bottom to keep you informed about your sessions, windows, and panes. I've also color coded the status bar to something a little more intuitively colored. 
    
    - Displays session name, window index, and pane information.
    - Color-coded for better visibility.
    
- **Mouse Support:**
    
    - Enables mouse interaction for a more intuitive experience.
    - Scroll through panes and resize them using the mouse.
    
- **Custom Key Bindings:**

    
    - Intuitive and ergonomic key bindings for common actions.
    - Check the configuration file for a comprehensive list.

- **Plugin Support:** Easily extend functionality with popular tmux plugins for additional uses.



If you'd like to contribute to this repository, please feel free to fork this repo and commit changes for approval. 
