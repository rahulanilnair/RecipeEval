# RecipeEval: A Comprehensive Study on Fine-tuning and Benchmarking Small Language Models for Open-ended Recipe Generation

This research presents a comprehensive exploration and study of recipe generation task by fine-tuning various small language models, with a focus on developing robust evaluation metrics and comparing across smaller language models the open ended task of recipe generation. This study presents extensive experiments with multiple model architectures, ranging from T5-small (Raffel et al., 2023) and SmolLM-135M (Allal et al., 2024) to Phi-2 (Re- search, 2023), implementing both traditional NLP metrics and custom domain-specific evaluation metrics. Our novel evaluation framework incorporates recipe specific metrics for assessing content quality and introduces an approach to allergen substitution. The results indicate that, while larger models generally perform better on standard metrics, the relationship between model size and recipe quality is more nuanced when considering domain specific metrics. We find that SmolLM-360M and SmolLM-1.7B demonstrate comparable performance despite their size difference, while Phi-2 shows limitations in recipe generation despite its larger parameter count. Our comprehensive evaluation framework and allergen substitution system provide valuable insights for future work in recipe generation and broader NLG tasks that require domain expertise and safety considerations.

[![License: Proprietary](https://img.shields.io/badge/License-Proprietary-red.svg)]()

## Proprietary Software Notice

This software project is proprietary. Unauthorized copying, transferring, or reproduction of this software, its source code, or documentation, via any medium, is strictly prohibited.

## Citation and Publication Policy

If you use this project in your research, please cite it as:

```
Vij, A., Bhowmick, A., Liu, C., Shi, E., Nair, R., & Ho, T.
Department of Computer Science
University of Southern California
Los Angeles, CA 90007
{anneketh, abhowmic, celiu, epshi, ranair, teho}@usc.edu
```

# Publication Rights

1. Any publications, papers, presentations, or other academic/research works that use or are based on this codebase MUST:
   - Obtain explicit written approval from repo owner before submission
   - Acknowledge the use of this codebase with proper citation

2. These requirements apply to:
   - Direct use of the code
   - Derivative works
   - Results obtained using this codebase
   - Methodologies or algorithms implemented in this codebase

3. Failure to comply with these terms constitutes both:
   - A violation of the software license
   - Academic misconduct/ethics violation
  
Copyright (c) 2025

All rights reserved.

No part of this software, including but not limited to the source code and documentation, may be reproduced, distributed, or transmitted in any form or by any means, including photocopying, recording, or other electronic or mechanical methods, without the prior written permission of the copyright holder.

For permission requests, please contact the repository owner.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
