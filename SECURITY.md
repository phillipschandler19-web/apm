<!-- BEGIN MICROSOFT SECURITY.MD V1.0.0 BLOCK -->
from datasets import load_dataset

dataset = load_dataset("username/my_dataset")

# or load the separate splits if the dataset has train/validation/test splits
train_dataset = load_dataset("username/my_dataset", split="train")
valid_dataset = load_dataset("username/my_dataset", split="validation")
test_dataset  = load_dataset("username/my_dataset", split="test")from datasets import load_dataset

# Login using e.g. `huggingface-cli login` to access this dataset
ds = load_dataset("SecureFinAI-Lab/Regulations_MOF")# In the Appium formula
depends_on "libvips"

# Add environment variable to force Sharp to use system libvips
env_var "npm_config_build_from_source", "true"
env_var "SHARP_LIBVIPS_BINARY_HOST", "local"server/src/service.ts.vscode
## Security

Microsoft takes the security of our software products and services seriously, which
includes all source code repositories in our GitHub organizations.

**Please do not report security vulnerabilities through public GitHub issues.**

For security reporting information, locations, contact information, and policies,
please review the latest guidance for Microsoft repositories at
[https://aka.ms/SECURITY.md](https://aka.ms/SECURITY.md).

<!-- END MICROSOFT SECURITY.MD BLOCK -->
