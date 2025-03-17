# LaunchHPC Site Update - Global Rules

## Overview

We are updating an Astro template site for LaunchHPC to reflect the new positioning of the company. LaunchHPC is now focused on the broader HPC and AI market, offering optimization and observability of existing workflows, and reselling NVIDIA DGX Cloud solutions.

## Key Guidelines

1. **Preserve Structure**: All markdown files in `./src/content` MUST maintain their exact same structure with their frontmatter intact.

2. **Update Content**: Replace mock content with accurate information from the positioning guide.

3. **Use Existing Assets**: Images should be referenced from `./public/images/product/` directory.

4. **Config Updates**: Update files in `./src/config` to align with the new positioning.

## Site Focus

The LaunchHPC site should focus on the following key elements:

1. **Enterprise AI & HPC Infrastructure**: Position LaunchHPC as a comprehensive solution for enterprise AI and high-performance computing needs.

2. **Key Differentiators**:

   - Elastic scaling between on-premise and cloud solutions
   - Advanced workload optimization capabilities
   - Comprehensive real-time observability
   - NVIDIA DGX Cloud integration and reselling
   - Enterprise-grade security and compliance

3. **Target Industries**: While previously focused on education, now target:

   - Financial services
   - Healthcare/Pharmaceutical
   - Retail analytics
   - Scientific research
   - General enterprise AI/ML operations

4. **Value Propositions**:
   - Performance acceleration
   - Resource optimization
   - Technical expertise access
   - Business agility
   - Risk reduction
   - Sustainable computing

## Content Structure

The site should be organized around the following sections, aligning with the positioning guide:

1. **Hero/Landing**: Introducing LaunchHPC as an enterprise HPC & AI infrastructure solution

2. **Platform Features**:

   - Simplified Deployment & Management
   - Advanced Workload Optimization
   - Comprehensive Observability
   - Enterprise-Scale Collaboration
   - Resilient Infrastructure
   - Enterprise Security & Compliance

3. **Use Cases/Industries**: Showcase applications in different sectors

   - AI Model Development & Deployment
   - Scientific Research & Simulation
   - Financial Modeling & Risk Analysis
   - Enterprise Data Analytics

4. **Differentiators**: Why choose LaunchHPC over alternatives

5. **Contact/CTA**: How to engage with the LaunchHPC team

## Specific File Update Guidelines

When updating files in `./src/content`:

1. **Preserve all YAML frontmatter** at the top of each markdown file
2. **Maintain the same heading structure** (H1, H2, H3, etc.)
3. **Keep the same markdown formatting elements** (lists, tables, code blocks, etc.)
4. **Update the text content** to align with the positioning guide
5. **Update image references** to point to files in `./public/images/product/`

## Config File Updates

For files in `./src/config`:

1. Update site metadata, navigation items, and footer information
2. Ensure all links point to the correct updated content
3. Update any feature flags or settings to enable new sections
4. Adjust color schemes and branding elements if needed

## Image Handling

1. Use existing images from `./public/images/product/`
2. If new images are needed, add them to this directory
3. Make sure all image references use relative paths from the project root
4. Optimize images for web if adding new ones

By following these guidelines, we ensure a consistent update of the LaunchHPC site while preserving the technical structure of the Astro template.
