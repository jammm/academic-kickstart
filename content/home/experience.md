+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

[[experience]]
  title = "Machine Learning Engineer, 3D"
  company = "Stability AI"
  company_url = "https://stability.ai/"
  location = "London, UK"
  date_start = "2024-03-01"
  date_end = ""
  description = """
  * Focusing on 3D neural rendering workloads and GPU optimizations.
  """

[[experience]]
  title = "Research Engineer"
  company = "Advanced Micro Devices (AMD)"
  company_url = "https://www.amd.com/en.html"
  location = "Tokyo, Japan"
  date_start = "2021-04-01"
  date_end = "2024-03-31"
  description = """
  R&D in Ray Tracing and Machine Learning for Neural Rendering.

  * Influenced multiple future hardware architectures on neural rendering by developing forward-looking workloads and evaluating them under different hardware constraints.

  * Developed an RDNA3 AI accelerated demo in 2.5 weeks, shown off at the Las Vegas launch event on November 3rd, using optimized fully fused MLP inference kernels and grid encoding. Inference kernels written from scratch using WMMA instructions for RDNA3 architecture. Demonstrated a 2.7x inference performance improvement on the 7900 XTX compared to the 6950 XT. Received an award by Rick Bergman for this effort. 

  * Wrote a blog on how to use RDNA3's WMMA instructions with sample code - https://gpuopen.com/learn/wmma_on_rdna3/ - well received both internally and externally.

  * Re-implemented instant-ngp (Instant NeRF) from scratch, which includes fully-fused MLP kernels with WMMA optimizations (tensor core usage), grid encoding and occupancy grids for in-house research work with competitive performance.

  * Ported tiny-cuda-nn and instant-ngp to HIP, supporting RDNA3 and MI GPUs, utilizing the WMMA ops of RDNA3 and matrix cores of MI.

  * Wrote a single .exe prototype for running stable diffusion on AMD GPUs using SHARK from nod.ai. Prototype adopted and used extensively in production today. Collaborated with nod.ai to get it running on RDNA3. Won the RTG Next 5% award from David Wang for this work.

  * Enabled Windows support of the ROCm backend for nod.ai SHARK (later acquired by AMD). Demonstrated the viability of the ROCm backend on Windows as a more flexible alternative to the Vulkan backend. Received an executive spotlight award for this work.

  * Enabled HIP support for llamafile and contributed towards RDNA3 compatibility for llama.cpp on Windows.

  Also worked on Radeon™ ProRender - Delivered massive CPU performance improvements and developed a HIP based backend for AMD GPUs, with an initial HIP port from OpenCL done within 48 hours.
  """

[[experience]]
  title = "Research Scientist (Part-Time)"
  company = "Rakuten Institute of Technology (RIT)"
  company_url = "https://rit.rakuten.co.jp/"
  location = "Tokyo, Japan"
  date_start = "2018-07-01"
  date_end = "2019-03-21"
  description = """
  * Research and implementation of soft-segment background removal of e-commerce product pictures using deep learning.
  """

[[experience]]
  title = "Architect / Lead software engineer"
  company = "Rakuten"
  company_url = "https://global.rakuten.com/en/"
  location = "Tokyo, Japan"
  date_start = "2016-10-01"
  date_end = "2019-03-21"
  description = """
  During my stint at the Ecosystem Services Department, I helped design and ship global scale web apps around the major ID platforms. I also worked horizontally across all ecosystem services (Points, Payments, Membership) to enhance technical quality across the board.
  	
  **Notable projects:**
  	
  * Design, develop and deploy a global-scale ID service layer using multi-regional kubernetes cluster with anycast routing using GCP. Service currently used by multiple Rakuten services across the globe, supporting hundreds of millions MAU.

  * Ebates+ID integration: Helped speed up production readiness for integration of the new ID platform with Ebates. Deployed core components closer to the ID data-centers in GCP for a massive decrease in login latency using HAProxy for fault tolerance.
  	
  * GCP integration with Rakuten's Data centers: As a consultant to the cloud and internal network teams, I helped setup and integrate GCP's cloud interconnect to all ESD projects which required connectivity to on-premise resources.

  **Roles and responsibilities as architect:**
  	
  * Cloud architect: Enforcing governance and principles of least privilege for all cloud users within the department; introduced real-time billing updates to senior management and also helped decrease yearly cloud bills by ~¥12 million. Introduced best practices for cloud security and consulted teams on optimal GCP usage and best practices.

  * Release reviews: Lead weekly release reviews of Points, Payments and Membership sections. Enforced the 3 pillars of a successful release - safe, repeatable and stress-free. This helped reduce release troubles and increase fully automated releases.

  * Mentorship: Mentored new engineers with their on-boarding and training, and organised training projects for interns from various Canadian universities as part of their co-op program. The training introduced them to new technologies, internal and external, and platforms including Docker, Kubernetes, Kotlin etc. as a way to help them get up to speed with ESD's existing projects.
	"""

[[experience]]
  title = "Intern programmer"
  company = "Ubisoft"
  company_url = "ubisoft.com"
  location = "Pune, India"
  date_start = "2016-01-01"
  date_end = "2016-05-09"
  description = """
  * Worked on the gameplay and engine layers, fixing flaky issues while porting and remastering South Park™: The Stick of Truth™ for PS4/Xbox One.
  """

+++
