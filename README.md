# nixos-llomam-configuration.nix

services.ollama = {
  enable = true;
  #package = pkgs.unstable.ollama;
  acceleration = "rocm"; # Or "cuda"
  #};
};

