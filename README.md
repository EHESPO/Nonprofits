# Microsoft for Nonprofits

This repository contains lightweight, open source solutions designed to help nonprofit and international development organizations achieve their missions. It is maintained by Microsoft’s Tech for Social Impact team whose goal is to empower every nonprofit and humanitarian organization to accelerate social good by providing access to relevant, affordable, and innovative cloud and AI solutions.

The solutions contained in this repository are accelerators designed to make it easier for ISV partners and other solution providers to create customized, industry-specific solutions.

## Table of Contents

- [Microsoft for Nonprofits](#microsoft-for-nonprofits)
  - [Table of Contents](#table-of-contents)
  - [Nonprofit Solutions](#nonprofit-solutions)
  - [Trademark](#trademark)

---

## Nonprofit Solutions

| **Solution**                                    | **Description**                                                                                                    | **Deploy** | **More info** |
|-------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|------------|---------------|
| [Azure Landing Zone for Nonprofits](./AzureLandingZoneforNonprofits/README.md) | Azure Landing Zone for Nonprofits is a preconfigured cloud environment that provides a blueprint to help set up core Azure services including networking, management, identity, and security. | [Deploy](./Documents/alz-build-and-deploy.md) | [Documentation](https://learn.microsoft.com/en-us/industry/nonprofit/azure-landing-zone) |
| [Common Data Model for Nonprofits](./CommonDataModelforNonprofits/README.md) | The Common Data Model for Nonprofits is an open source data schema that reflects nonprofit industry best practices. It promotes cross-solution and cross-organization data interoperability, enabling powerful insights across activities and departments. | [Deploy](./Documents/dataverse-build-and-deploy.md) | [Documentation](https://aka.ms/DocsCDMforNonprofits) |
| [Fundraising](./Fundraising/README.md)                     | Fundraising provides partners with a flexible, easily extensible foundation for building fundraising solutions for nonprofit customers. | [Deploy](./Documents/dataverse-build-and-deploy.md) | [Documentation](https://learn.microsoft.com/en-us/industry/nonprofit/fundraising) |
| [Grant Management](./GrantManagement/README.md)           | Grant Management provides partners with a flexible, easily extensible foundation for building grant management solutions for nonprofit customers. | [Deploy](./Documents/dataverse-build-and-deploy.md) | [Documentation](https://learn.microsoft.com/en-us/industry/nonprofit/grant-management) |
| [Nonprofit data solutions in Microsoft Fabric](./NonprofitDataSolutions/Fundraising/README.md) | Nonprofit data solutions in Microsoft Fabric consist of a preconfigured, scalable data architecture and analytics framework designed to help nonprofit organizations unify, transform, and analyze their data. | [Deploy](https://learn.microsoft.com/en-us/industry/nonprofit/deploy-nonprofit-data-solutions) | [Documentation](https://learn.microsoft.com/en-us/industry/nonprofit/nonprofit-data-solutions-overview) |
| [Outcome Management](./OutcomeManagement/README.md)       | Outcome Management provides partners with a flexible, easily extensible foundation for building program measurement solutions for nonprofit customers. | [Deploy](./Documents/dataverse-build-and-deploy.md) | [Documentation](https://learn.microsoft.com/en-us/industry/nonprofit/outcome-management) |
| [Volunteer Engagement](./VolunteerEngagement/README.md)   | Volunteer Engagement is a Power Pages React SPA where volunteers can find and apply for engagement opportunities. | [Deploy](./VolunteerEngagement/Portal-EDM/README.md) | [Documentation](./VolunteerEngagement/README.md) |
| [Volunteer Management](./VolunteerManagement/README.md)   | Volunteer Management is a Power App that enables the management of day-to-day processes to recruit, onboard, and retain volunteers. | [Deploy](./Documents/dataverse-build-and-deploy.md) | [Documentation](https://learn.microsoft.com/en-us/industry/nonprofit/volunteer-management-use) |

---

## Trademark

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow Microsoft’s [Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party’s policies.

<?php
// ============================================================
// PRODUCT OFFERS PAGE – EHEPS ORGANIZATION (UPDATED)
// Added: GitHub, MCP, Atlassian (already present)
// ============================================================

// ------------------------------------------------------------
// CONFIGURATION
// ------------------------------------------------------------
$domains      = ['eheps.org', 'eheps.com'];
$owner_email  = 'ewaz.2010@gmail.com';
$super_admins = [
    'Executive@eheps.co'      => 'Super Admin',
    'Executivedirector@eheps.org' => 'Super Admin'
];

// ------------------------------------------------------------
// OFFERS DATA
// ------------------------------------------------------------
$top_tools = [
    ['name' => 'Adobe Express', 'desc' => 'Create and scale your impact for free on web and mobile.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Adobe Acrobat Pro', 'desc' => 'Save 94% on the essential document solution for nonprofits.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Claude', 'desc' => 'Elevate your nonprofit’s writing, research, and daily work with Claude AI at ~70% off.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Hootsuite', 'desc' => 'Optimize social media with 60% off Hootsuite.', 'btn' => 'Buy now', 'link' => '#'],
    ['name' => 'Microsoft 365 Business Premium', 'desc' => '75% off for eligible nonprofits.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'Microsoft 365 Copilot', 'desc' => '15% discount for eligible nonprofits.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'Microsoft Azure Grant', 'desc' => '$2,000 (USD) Azure services credits per year.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'Microsoft Power Apps', 'desc' => 'Free for up to 10 users, $2.50/user/month after.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'monday.com', 'desc' => '10 free users and 70% off additional seats.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'OpenAI', 'desc' => 'ChatGPT Team at $8/user/month or up to 75% off Enterprise.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Zoom', 'desc' => '50% off Zoom for nonprofits.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Docusign', 'desc' => 'Up to 50% off IAM and 30% off eSignature.', 'btn' => 'Buy now', 'link' => '#'],
];

$expert_services = [
    ['name' => 'YouDoGood marketing', 'desc' => 'High-impact short-form video and expert social services.', 'btn' => 'Learn more', 'link' => '#']
];

$discounted_software = [
    ['name' => 'Adobe Acrobat Pro', 'desc' => 'Save 94% on the essential document solution.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Adobe Express', 'desc' => 'Create and scale your impact for free.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Asana', 'desc' => '50% off Asana’s work management tools.', 'btn' => 'Buy now', 'link' => '#'],
    ['name' => 'Atlassian', 'desc' => '75% off Jira, Confluence, and Trello for better work management.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Auth0', 'desc' => '50% off Auth0’s advanced security tools.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Bugle', 'desc' => 'Free volunteer management with Bugle’s Community Plan.', 'btn' => 'Get started free', 'link' => '#'],
    ['name' => 'Canva', 'desc' => 'Design high-impact marketing materials, 100% free.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Claude', 'desc' => 'Elevate writing and research with Claude AI at ~70% off.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Constant Contact', 'desc' => 'Up to 35% off marketing automation tools.', 'btn' => 'Start free trial', 'link' => '#'],
    ['name' => 'Docusign', 'desc' => 'Up to 50% off IAM and 30% off eSignature.', 'btn' => 'Buy now', 'link' => '#'],
    ['name' => 'Easy Board', 'desc' => '20% off board and committee management.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'Eventbrite', 'desc' => '50% off Eventbrite’s premium ticketing.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'GitLab', 'desc' => 'Up to 20 free seats, plus discounts on additional seats.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Givebutter', 'desc' => 'Free all-in-one fundraising platform.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Google', 'desc' => '70%+ off Workspace and Ad Grants (Google for Nonprofits).', 'btn' => 'Apply', 'link' => 'https://www.google.com/nonprofits/'],
    ['name' => 'Keela', 'desc' => '10% off Keela’s nonprofit CRM with AI-powered tools.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'AI for Community training', 'desc' => 'Live instructor-led training on AI tools for nonprofits.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'Goodstack Grants Pro', 'desc' => 'Discover grant opportunities with AI assistant Maia.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'Gusto', 'desc' => 'First month free on online payroll and benefits.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'Hootsuite', 'desc' => '60% off social media management.', 'btn' => 'Buy now', 'link' => '#'],
    ['name' => 'LinkedIn Fundraise', 'desc' => '75% off LinkedIn Sales Navigator Core.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Microsoft', 'desc' => 'Savings on Azure, Dynamics 365, and Microsoft 365.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Microsoft 365 Business Premium', 'desc' => '75% off for eligible nonprofits.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'Microsoft 365 Copilot', 'desc' => '15% discount on AI assistant.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'Microsoft Azure Grant', 'desc' => '$2,000 (USD) Azure credits per year.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'Microsoft Power Apps', 'desc' => 'Free for 10 users, $2.50/month after.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'monday.com', 'desc' => '10 free users and 70% off additional seats.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'N2F', 'desc' => '20% off expense management solution.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'New Relic', 'desc' => '1,000 GB data and three free full-platform users.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'NordLayer', 'desc' => '40% off network security solutions.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'Okta', 'desc' => '50% off secure identity solutions.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'OpenAI', 'desc' => 'ChatGPT Team at $8/user/month or up to 75% off Enterprise.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Sage', 'desc' => '50% off Sage Intacct accounting.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Splunk', 'desc' => 'Big data tools, free for nonprofits.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Twilio', 'desc' => '$100 credits and discounts on communications tools.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Workvivo', 'desc' => '50% off employee engagement platform.', 'btn' => 'Apply', 'link' => '#'],
    ['name' => 'Zoom', 'desc' => '50% off collaboration and communication solutions.', 'btn' => 'Apply', 'link' => '#'],
    // --- NEW ADDITIONS ---
    ['name' => 'GitHub', 'desc' => 'GitHub Global Campus for Nonprofits – free GitHub Team for eligible organizations, plus discounted GitHub Copilot for your development teams.', 'btn' => 'Apply', 'link' => 'https://github.com/nonprofit/'],
    ['name' => 'MCP (Model Context Protocol)', 'desc' => 'Leverage AI agent capabilities with MCP – enabling seamless integrations, data access, and advanced automation for your nonprofit projects and workflows.', 'btn' => 'Learn more', 'link' => '#'],
];

// Featured offers (Top of page)
$featured = [
    ['name' => 'Adobe Acrobat Pro', 'desc' => 'Save 94% on the essential document solution for nonprofits.', 'btn' => 'Apply now', 'link' => '#'],
    ['name' => 'Zoom', 'desc' => 'Empower your nonprofit with an exclusive 50% discount on Zoom\'s collaboration solutions.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'LinkedIn', 'desc' => '75% discount on LinkedIn\'s hiring and fundraising solutions.', 'btn' => 'Get started', 'link' => '#'],
    ['name' => 'Claude', 'desc' => 'Elevate your nonprofit’s writing and research with Claude AI at ~70% off.', 'btn' => 'Apply here', 'link' => '#'],
    ['name' => 'Microsoft', 'desc' => 'Power your nonprofit with free technology grants and discounts.', 'btn' => 'Get started', 'link' => '#'],
];
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Offers – EHEPS Organization</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body { background: #f8f9fa; }
        .sidebar-link { color: #6c757d; text-decoration: none; padding: 0.5rem 1rem; display: block; }
        .sidebar-link:hover, .sidebar-link.active { background: #e9ecef; border-radius: 0.375rem; color: #0d6efd; }
        .offer-card { transition: transform 0.2s; border: none; box-shadow: 0 2px 4px rgba(0,0,0,0.05); }
        .offer-card:hover { transform: translateY(-3px); box-shadow: 0 8px 16px rgba(0,0,0,0.1); }
        .banner-grants { background: #fff3cd; border: 1px solid #ffc107; border-radius: 0.5rem; padding: 1rem; }
        .footer { border-top: 1px solid #dee2e6; margin-top: 3rem; padding: 2rem 0; }
        .search-bar { max-width: 500px; }
    </style>
</head>
<body>
    <!-- Top Bar -->
    <div class="container py-2 d-flex justify-content-end align-items-center gap-3">
        <span class="text-muted small">EN</span>
        <a href="#" class="text-decoration-none text-primary">Get in touch</a>
    </div>

    <!-- Main Container -->
    <div class="container my-4">
        <div class="row">
            <!-- Sidebar -->
            <div class="col-lg-3 col-md-4 mb-4">
                <nav class="nav flex-column">
                    <a href="#" class="sidebar-link">Home</a>
                    <a href="#" class="sidebar-link">Profile</a>
                    <a href="#" class="sidebar-link">Donations</a>
                    <a href="#" class="sidebar-link">Payouts</a>
                    <a href="#" class="sidebar-link active">Product offers</a>
                    <a href="#" class="sidebar-link">My discounts</a>
                    <a href="#" class="sidebar-link">Grant Assistant</a>
                    <a href="#" class="sidebar-link">Goodstack Pro</a>
                </nav>
                <div class="banner-grants mt-4">
                    <strong>We have grants waiting for you!</strong>
                    <div class="mt-2"><a href="#" class="btn btn-warning btn-sm w-100">Apply now</a></div>
                </div>
            </div>

            <!-- Main Content -->
            <div class="col-lg-9 col-md-8">
                <!-- Header -->
                <div class="d-flex align-items-start gap-3 mb-4">
                    <div class="bg-light rounded-circle d-flex align-items-center justify-content-center" style="width: 80px; height: 80px; font-size: 2.5rem; color: #6c757d;">
                        <i class="bi bi-boxes"></i>
                    </div>
                    <div>
                        <h2 class="mb-1">Mohammad ewaz Nazari</h2>
                        <p class="text-muted mb-0">Owner</p>
                        <small class="text-muted"><?= $owner_email ?></small>
                    </div>
                </div>

                <!-- Search -->
                <h3 class="mb-3">Product offers</h3>
                <div class="mb-4">
                    <label class="form-label fw-bold">What are you looking for?</label>
                    <div class="input-group search-bar">
                        <input type="text" class="form-control" placeholder="Search for tools or key words">
                        <button class="btn btn-outline-secondary" type="button">Search</button>
                    </div>
                </div>

                <!-- Featured -->
                <h5 class="mt-4 mb-3">Featured deals</h5>
                <div class="row g-3 mb-4">
                    <?php foreach ($featured as $item): ?>
                    <div class="col-md-6 col-lg-4">
                        <div class="card offer-card h-100">
                            <div class="card-body d-flex flex-column">
                                <h6 class="card-title fw-bold"><?= htmlspecialchars($item['name']) ?></h6>
                                <p class="card-text small text-muted flex-grow-1"><?= htmlspecialchars($item['desc']) ?></p>
                                <a href="<?= htmlspecialchars($item['link']) ?>" class="btn btn-outline-primary btn-sm mt-2 align-self-start"><?= $item['btn'] ?></a>
                            </div>
                        </div>
                    </div>
                    <?php endforeach; ?>
                </div>

                <!-- Top Tools -->
                <h5 class="mt-4 mb-3">Top tools and resources</h5>
                <div class="row g-3 mb-4">
                    <?php foreach ($top_tools as $item): ?>
                    <div class="col-md-6 col-lg-4">
                        <div class="card offer-card h-100">
                            <div class="card-body d-flex flex-column">
                                <h6 class="card-title fw-bold"><?= htmlspecialchars($item['name']) ?></h6>
                                <p class="card-text small text-muted flex-grow-1"><?= htmlspecialchars($item['desc']) ?></p>
                                <a href="<?= htmlspecialchars($item['link']) ?>" class="btn btn-outline-primary btn-sm mt-2 align-self-start"><?= $item['btn'] ?></a>
                            </div>
                        </div>
                    </div>
                    <?php endforeach; ?>
                </div>

                <!-- Expert Services -->
                <h5 class="mt-4 mb-3">Expert services</h5>
                <div class="row g-3 mb-4">
                    <?php foreach ($expert_services as $item): ?>
                    <div class="col-md-6 col-lg-4">
                        <div class="card offer-card h-100">
                            <div class="card-body d-flex flex-column">
                                <h6 class="card-title fw-bold"><?= htmlspecialchars($item['name']) ?></h6>
                                <p class="card-text small text-muted flex-grow-1"><?= htmlspecialchars($item['desc']) ?></p>
                                <a href="<?= htmlspecialchars($item['link']) ?>" class="btn btn-outline-primary btn-sm mt-2 align-self-start"><?= $item['btn'] ?></a>
                            </div>
                        </div>
                    </div>
                    <?php endforeach; ?>
                </div>

                <!-- Discounted Software (including GitHub & MCP) -->
                <h5 class="mt-4 mb-3">Discounted software</h5>
                <div class="row g-3">
                    <?php foreach ($discounted_software as $item): ?>
                    <div class="col-md-6 col-lg-4">
                        <div class="card offer-card h-100">
                            <div class="card-body d-flex flex-column">
                                <h6 class="card-title fw-bold"><?= htmlspecialchars($item['name']) ?></h6>
                                <p class="card-text small text-muted flex-grow-1"><?= htmlspecialchars($item['desc']) ?></p>
                                <a href="<?= htmlspecialchars($item['link']) ?>" class="btn btn-outline-primary btn-sm mt-2 align-self-start"><?= $item['btn'] ?></a>
                            </div>
                        </div>
                    </div>
                    <?php endforeach; ?>
                </div>
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer class="footer">
        <div class="container text-center">
            <p class="mb-1"><strong>Domains:</strong> 
                <?php foreach ($domains as $d): ?>
                    <a href="https://<?= $d ?>" target="_blank"><?= $d ?></a> &nbsp;
                <?php endforeach; ?>
            </p>
            <p class="mb-0">
                <strong>Contact:</strong> 
                <?php foreach ($super_admins as $email => $role): ?>
                    <a href="mailto:<?= $email ?>"><?= $email ?></a> (<?= $role ?>) &nbsp;|&nbsp;
                <?php endforeach; ?>
                <a href="mailto:<?= $owner_email ?>"><?= $owner_email ?></a> (Owner)
            </p>
            <p class="mt-2 small text-muted">&copy; 2026 EHEPS Organization. All rights reserved.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
