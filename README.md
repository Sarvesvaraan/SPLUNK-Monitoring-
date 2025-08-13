# SPLUNK-Monitoring-
Designed and implemented a SIEM use case using Splunk to monitor and analyze simulated Linux host and web server logs. Developed custom dashboards, alerts, and lookup-based enrichments for real-time threat detection. Configured field extractions, role-based access, summary indexing, and drilldowns to simulate end-to-end SOC workflows.

## **What You Did in This Project**

1. **Planned a Unified Splunk Monitoring Solution**

   * Designed a project titled **"Unified Host and Web Log Monitoring with Alerting and Data Compliance in Splunk"**.
   * Combined Linux host intrusion detection with web access log analytics.

2. **Set Up Splunk Environment**

   * Installed and configured **Splunk Enterprise** and **Splunk Universal Forwarder**.
   * Used a **Deployment Server** for central configuration management.

3. **Log Collection**

   * Simulated Linux system logs and Apache access logs in `/var/log/fake_logs/`.
   * Configured Splunk UF to forward logs with a **common sourcetype** (`linux_logs`).

4. **Indexing & Data Organization**

   * Created dedicated **indexes** for better data segregation.
   * Applied **props.conf** and **transforms.conf** for field extractions.

5. **Data Enrichment**

   * Created **lookup tables** aligned with your fake log data.
   * Applied **automatic field lookups** for context (e.g., mapping usernames, IPs, or status codes).

6. **Tags & Event Types**

   * Tagged events for easy classification (e.g., suspicious activity, normal access).
   * Defined **event types** for filtering and categorizing log patterns.

7. **Dashboards & Visualizations**

   * Built visual dashboards for **host activity**, **web traffic patterns**, and **security alerts**.
   * Added **drilldowns** for deeper investigation.

8. **Advanced Splunk Features**

   * Configured **summary indexing** for faster reporting.
   * Created **search macros** for reusable SPL logic.
   * Set up **custom alerts** with notifications.

9. **Data Compliance**

   * Applied **data masking** for sensitive information.
   * Enforced **role-based access control (RBAC)** for Splunk users.

10. **Final Steps**

    * Packaged the Splunk app for deployment.
    * Performed cleanup and optimization.

---

## **What You Learned**

* **Splunk Fundamentals**

  * Installing and configuring Splunk Enterprise & UF.
  * Indexing, sourcetypes, field extractions.

* **Log Management**

  * Handling multiple log sources (Linux + Apache).
  * Creating realistic simulated logs for testing.

* **Data Enrichment & Context**

  * Creating and using lookups.
  * Tagging and classifying events.

* **Advanced Splunk Admin Skills**

  * Deployment server configuration.
  * Summary indexing & search optimization.
  * Role-based access control and compliance considerations.

* **Visualization & Analysis**

  * Designing functional dashboards with drilldowns.
  * Writing SPL queries for detection and reporting.

* **Security Monitoring Workflow**

  * Detecting anomalies in logs.
  * Creating alerts for suspicious activity.

---

## **Key Takeaways**

1. **Hands-on SIEM Implementation** — You built a **full-featured Splunk monitoring system** from scratch.
2. **Log Pipeline Knowledge** — You now understand **end-to-end log flow** from collection to visualization.
3. **Data Compliance Awareness** — You applied privacy, masking, and access control best practices.
4. **Incident Investigation Skills** — You learned how to classify, tag, and drill down into suspicious events.
5. **Scalable Design Thinking** — You structured your Splunk setup in a way that can be extended for real-world environments.
6. **Problem-Solving** — You overcame challenges like fake log generation, realistic lookup creation, and field extractions.

---

If you want, I can also make a **short, professional "Resume Version"** of this so it fits in a *Work/Projects* section perfectly.
That way, it’ll be hiring-manager friendly.
![WhatsApp Image 2025-08-13 at 4 52 05 PM](https://github.com/user-attachments/assets/63ae2a98-cf05-46e4-a6f1-a969671fbb9f)

![WhatsApp Image 2025-08-13 at 4 52 05 PM (1)](https://github.com/user-attachments/assets/7bd7008a-89e6-45cf-80b6-9806ad2cbf41)

![WhatsApp Image 2025-08-13 at 4 52 05 PM (2)](https://github.com/user-attachments/assets/60c28320-c3d0-4dcb-b526-5c2e8dd1705e)
